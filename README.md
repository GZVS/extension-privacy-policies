# Extension Privacy Policies

Privacy-policy source files for browser extensions by **GZVS**.

Suggested repository: `GZVS/extension-privacy-policies`  
Suggested description: `Privacy policies for Chrome and Microsoft Edge extensions by GZVS.`

## Policies

Each extension has its own `privacy.md` file so its policy can be updated independently.
These starter files are visibly marked as drafts. They contain no verified claims about extension behavior.

| Extension | Policy file | Status |
| --- | --- | --- |
| Silent YouTube | [silent-youtube/privacy.md](extensions/silent-youtube/privacy.md) | Draft |
| YouTube Music Visualizer | [youtube-music-visualizer/privacy.md](extensions/youtube-music-visualizer/privacy.md) | Draft |
| NjoyYourMusic | [njoyyourmusic/privacy.md](extensions/njoyyourmusic/privacy.md) | Draft |
| TinyShield | [tinyshield/privacy.md](extensions/tinyshield/privacy.md) | Draft |
| Edge Music | [edge-music/privacy.md](extensions/edge-music/privacy.md) | Draft |

## Create the GitHub repository

1. Open https://github.com/new and select owner **GZVS**.
2. Name it **extension-privacy-policies**, enter the suggested description, and select **Public** so policy links can be opened without signing in.
3. Leave the initial README, license and gitignore options unchecked; this package supplies the README.
4. Create the repository, extract this ZIP locally, and open the extracted `extension-privacy-policies` folder.
5. In GitHub, choose **Add file → Upload files**. Drag the contents of the extracted folder into the upload area, including the `extensions` and `templates` folders. Commit to `main`.

## Finish a policy

1. Review the extension's released source, manifest, storage APIs and network behavior.
2. Replace every bracketed field with accurate details. Add a public support email or private support form.
3. Remove the draft banner only after checking the finished policy against the released extension and the store's data disclosures.
4. Update the effective date and this table's status. Keep the same path for future revisions.

## Policy URLs

Once uploaded to the public repository on `main`, a policy's GitHub URL follows this pattern:

`https://github.com/GZVS/extension-privacy-policies/blob/main/extensions/<extension-slug>/privacy.md`

For example, the planned TinyShield URL is:

`https://github.com/GZVS/extension-privacy-policies/blob/main/extensions/tinyshield/privacy.md`

These are planned URLs until the repository and files have been uploaded. Open the finished policy URL while signed out before submitting it. Use the extension's specific policy link in the store's Privacy Policy URL field; do not link to the root README or to a draft.

## Add another extension

Create `extensions/<new-extension-slug>/privacy.md` from `templates/privacy-template.md`, complete it, and add it to the table above.

## Store documentation

- [Chrome Web Store privacy policy requirements](https://developer.chrome.com/docs/webstore/program-policies/privacy)
- [Chrome Web Store Limited Use requirements](https://developer.chrome.com/docs/webstore/program-policies/limited-use)
- [Microsoft Edge extension publishing](https://learn.microsoft.com/en-us/microsoft-edge/extensions/publish/publish-extension)

Store disclosures and policy text must reflect the extension's actual handling of information. A shared repository is a place to host separate policies, not a substitute for reviewing each extension.
