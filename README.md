# tongflow-modal-gemma4

Official [TongFlow](https://github.com/tong-io/tongflow) plugin. Multimodal understanding with **Gemma-4** (`google/gemma-4-E4B-it`), running on a GPU via [Modal](https://modal.com). Describes or answers questions about images and video.

## Capabilities

- **Image understanding** (`image-gen-text`) — captions, Q&A, or descriptions from an image.
- **Video understanding** (`video-gen-text`) — summaries or descriptions from a video.

## Credentials

Add in TongFlow **Settings** (gear icon, top-right):

| Key | Required | Notes |
| --- | --- | --- |
| `MODAL_TOKEN_ID` | ✅ | Create at [modal.com/settings/tokens](https://modal.com/settings/tokens). |
| `MODAL_TOKEN_SECRET` | ✅ | Paired with `MODAL_TOKEN_ID`. |

On first use the plugin deploys to your Modal account automatically and caches the build. The `google/gemma-4-E4B-it` weights are public — no Hugging Face token required.
