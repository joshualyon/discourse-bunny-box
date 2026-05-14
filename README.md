# discourse-bunny-box
OneBox formatting for Bunny.net stream embeds

## Additional Configuration
You may need to update the Discourse Settings > Security > Allowed iframes to allow the Bunny Stream domains to be iframed. Search: `allowed_iframes`
- New Player: `https://player.mediadelivery.net/`
- Old Player: `https://iframe.mediadelivery.net/`

The old `iframe.mediadelivery.net` URLs seemed to automatically get identified as iframeable on both the standard `/play/` URL path that you copy from the 'Direct Playback' in Bunny as well as the specific iframe `/embed/` URL path. 

The new `player.mediadelivery.net` only seems to automatically get iframed with the `/embed/` path so you may need to update the URL accordingly after copying it. 