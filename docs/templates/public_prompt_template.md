# Public Prompt Template (Safe Pattern)

This is a **generic** template meant to demonstrate structure and best practices.
It is not production logic and does not include proprietary policy details.

```text
<task>
Generate short-form notification copy for an e-commerce item:
1) a cleaned short title
2) a notification title (behavioral recall)
3) a notification body (context + gentle action)
</task>

<input>
raw_title: <RAW_TITLE>
category: <CATEGORY>
attributes: <ATTRIBUTES_MAP>   # optional
badges: <BADGES_LIST>          # optional (e.g., verified/authenticated)
offer: <OFFER>                 # optional (e.g., discount/coupon)
price: <PRICE>                 # optional
</input>

<output>
Return ONLY JSON.
If blocked:
{"status":"blocked","reason":"short reason"}

Otherwise:
{
  "short_title": "...",
  "notification_title": "...",
  "notification_body": "..."
}
</output>

<constraints>
- Recognition first: the user should clearly recognize the specific item.
- Safety screen: block disallowed content per applicable marketplace policies.
- Keep language calm, clear, and non-alarmist.
- Avoid unverifiable claims and invented details.
- Character limits:
  short_title ≤ 45
  notification_title ≤ 40
  notification_body ≤ 90
- Notification body: do not repeat the item name; add new value and end with a gentle CTA.
</constraints>
