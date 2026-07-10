# Privacy and safety — Pelvic Pause

**Effective date: July 10, 2026.** This policy describes the Pelvic Pause Chrome extension version 0.2.1.

Your progress stays on your device.

| | | |
|---|---|---|
| **No account** | **No browsing access** | **No data transfer** |
| No name, email, phone number, or advertising identifier is required. | The extension does not read web pages, URLs, forms, or browsing history. | The MVP does not send settings or exercise history to a developer server. |

## How the extension works

Pelvic Pause schedules reminders inside time windows chosen by the user. A system notification can open a short guided session or be snoozed. Completed-session progress is shown in the extension popup.

## Data stored locally

Chrome's extension storage is used for:

- Reminder days, time windows, daily goal, duration, and notification wording.
- Generated reminder plans and snooze status.
- Completed or ended sessions, including timestamps, duration, and whether the completion threshold was reached.
- Basic extension state needed to prevent duplicate reminders and sessions.

This information is stored in `chrome.storage.local`. It is removed when the extension is uninstalled. It can be exported as a JSON file or deleted at any time from Settings → Data & privacy. Exported files are created locally by the browser and are not sent to the developer.

## Permissions

- **alarms:** schedules reminders inside the time windows you choose.
- **notifications:** displays reminders with Start and Snooze actions.
- **storage:** saves settings and progress locally in the browser.

The extension declares no host permissions and contains no content scripts. It cannot inspect the contents of websites.

## Analytics, advertising, and third parties

The MVP contains no analytics SDK, advertising SDK, tracking pixel, remote executable code, or third-party data sale. It makes no network requests during normal operation.

## Custom notification text

Custom notification wording is stored locally and is not transmitted. Avoid entering sensitive information that you would not want displayed by your operating system's notification center.

## Safety information

**Pelvic Pause provides reminders and general exercise guidance only. It does not diagnose or treat medical conditions and does not replace advice from a doctor or pelvic health physiotherapist.**

Use gentle effort, keep breathing, avoid squeezing the glutes, thighs, or abdomen, and fully release after every contraction. Stop if you experience pain, spasm, difficulty urinating, worsening symptoms, or other significant discomfort.

Ask a qualified professional before using the exercise guide when you cannot identify the correct muscles, have an existing pelvic floor condition, are recovering from surgery, are pregnant or postpartum, or have another health situation that may require individualized guidance.

A brief, one-time attempt to interrupt urine flow may help identify the muscles, but repeated training while urinating is not recommended.

## Children

Pelvic Pause is not designed to collect personal information from children. The MVP does not collect personal information from any user.

## Changes to this policy

If a future version adds optional synchronization, analytics, accounts, or server features, the extension and public privacy policy must be updated before those features are released. Material changes should be clearly disclosed.

## Support / 联系方式

For questions about this privacy policy, please use the publisher contact email or support channel shown on the Chrome Web Store listing.

如对本隐私政策有疑问，请使用 Chrome 应用商店商品详情中显示的发布者联系邮箱或支持渠道。
