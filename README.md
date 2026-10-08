# Aixio — Image to Layer
Aixio Image to Layer is Aixio’s own model and the primary capability of this plugin. Convert an authorized image into image and text layers, inspect their positions and stacking order, and use the returned layers in your editing workflow. Complementary Seedream 5.0 Pro, Seedream 5.0 Lite, Nano Banana 2 and Seedance 2.5 operations are exposed only when enabled. These supporting models are not represented as Aixio-owned models. They can create or edit a source image or animate a selected result when requested; the plugin never runs an extra paid step automatically.

## Primary examples

- “Use Aixio Image to Layer to convert this poster into editable layers.”
- “Convert this diagram and show its returned text and image layers.”
- “Generate a campaign image, then use Aixio Image to Layer on the result.”

See [Image to Layer showcase inputs](./assets/image-to-layer/README.md) for selected poster and diagram examples. They are example inputs, not verified decomposition results.

Connect your Aixio account in the host's sign-in window. Review the app name,
account and permissions, then approve. You do not need to paste an API key.
New accounts use Aixio's normal signup credit policy; connecting again never
adds another signup grant. Models charge the same wallet used on Aixio.

Use the existing entitlements and balance in your Aixio account. The plugin does not sell credits or initiate purchases.
Disconnect apps at https://aixio.app/developers?tab=connections. Disconnecting
blocks access without cancelling jobs already accepted.

Inspect the exposed model operation tools and their typed input schemas. Check
`balance`, call the selected model operation after user authorization, then save
its job ID and retrieve `status` at the returned polling interval. A tool timeout does not mean the job failed. Resume the same job;
never submit a replacement automatically. Results may contain assets, text,
editable layers, or a truthful error. Signed result links expire; retrieve the
job again to refresh them.

For image-to-layer, discover Aixio Layer v1 and prepare an image upload. Upload
file bytes with a supported host file/HTTP tool before submitting its source
URL and required output dimensions. The connection cannot read local files.

This package is prepared for hosted distribution. Availability depends on the
hosted service being activated and the directory's review and publication.

## Privacy and support

Selected uploads, prompts, generation settings and account-linked job records are sent to Aixio. Generation inputs may be processed by the model services used by Aixio. Do not upload files without permission. Read https://aixio.app/legal/privacy for the service privacy policy and https://aixio.app/legal/terms for service terms. Contact support@aixio.app for account or integration support.

## Limits

Supported operations and accepted settings appear in the MCP tool list. Use the account’s model pricing shown on Aixio; do not invent prices from tool names. Generation requires sufficient credits and enabled API admission. A model may return a failure or flattened layer fallback; the plugin reports these faithfully. Host file upload capability is required for media inputs.
