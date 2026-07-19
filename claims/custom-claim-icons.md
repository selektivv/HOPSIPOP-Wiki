# Custom Claim Icons

Claim owners can replace the default head shown for an owned claim in the Claims GUI with a custom skull texture.

<img width="715" height="368" alt="Set Custom Icon control in the claim management menu" src="https://github.com/user-attachments/assets/70ec7e6f-fa1c-4c33-8599-199d7278ec29" />

## Find a Texture Value

1. Browse for a head on [minecraft-heads.com](https://minecraft-heads.com/).
2. Open the head's texture information.
3. Copy the complete **Value** field from the texture tab. A valid value for this menu starts with `ey`.

Copy the texture Value itself, not the page URL, image URL, Minecraft command, or texture ID.

## Set the Icon

1. Open `/claimgui`, or use `/mc` → **Shortcuts** → **Claims**.
2. Select a claim you own.
3. Click **Set Custom Icon**. The menu closes and provides a clickable link to the head website.
4. Paste the copied Value into chat and send it.

The input is intercepted by the server and is not posted to public chat or Discord. The server accepts values that start with `ey`, saves the complete text, and reopens the claim management menu.

If the text does not start with `ey`, no change is made. Open **Set Custom Icon** again before retrying. Paste the complete Value to avoid an icon that cannot render correctly.

## Reset the Icon

Open **Set Custom Icon** and enter `reset` in chat. This removes the stored texture and restores the default claim icon.

Custom icons are owner-only and affect the claim's head in the owner's claims list. Trusted players and Managers cannot change them. The icon is cosmetic and does not change claim permissions or behavior.

## Continue Learning

- [Manage a Claim](managing-a-claim.md)
- [Rename a Claim](renaming-a-claim.md)
- [Claims Overview](../claims.md)
