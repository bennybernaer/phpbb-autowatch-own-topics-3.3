# Changelog

All notable changes to this extension are documented here.

## 1.0.0 - 2026-10-31

### Added
- UCP preference under **Board preferences → Edit posting defaults**.
- Automatic subscription to every newly created own topic.
- One-time import of existing own topics when the preference is enabled.
- English and Dutch language support.
- Universal `styles/all` template event support.

### Behaviour
- Uses phpBB's native `topics_watch` subscriptions, so subscriptions remain visible and manageable through phpBB itself.
- Prevents duplicate subscriptions when a topic is already watched.
- Respects the global topic-notification setting and the `f_subscribe` permission.
- Does not remove existing subscriptions when the preference is disabled.
- Respects manual per-topic unsubscribe choices while the preference remains enabled.

### Compatibility
- phpBB 3.3.x build prepared from the phpBB 4 version on request.
- Requires PHP 7.4 or newer.
- This phpBB 3.3 build has not been tested by the author on a phpBB 3.3 installation.
