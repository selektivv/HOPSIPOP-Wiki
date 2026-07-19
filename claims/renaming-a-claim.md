# Renaming a Claim

Claim owners can replace the generated claim label with a custom name of up to 32 characters.

<img width="700" height="369" alt="Claim Info control used to rename a claim" src="https://github.com/user-attachments/assets/c4edcec0-5eec-4672-8a50-3a400e18ef00" />

## Set a Name

1. Open `/claimgui`, or use `/mc` → **Shortcuts** → **Claims**.
2. Select a claim you own.
3. Click **Claim Info**. The menu closes and asks for a name in chat.
4. Type the new name and send it.

Leading and trailing spaces are removed. The chat input is intercepted by the server and is not posted to public chat or Discord.

A name longer than 32 characters is rejected. Rename mode remains active, so you can immediately send a shorter name without reopening the menu. A valid name is saved and the claim management menu reopens.

## Reset the Name

Click **Claim Info** again and enter `reset` in chat. This removes the stored custom name.

The owned-claims list returns to a generated label such as **Claim #1**. The management menu returns to its default **Manage Claim** title, and Claim Info no longer shows a custom Name line. Because `reset` is reserved for this action, it cannot be used as a literal claim name.

## Where the Name Appears

The custom name is used for the claim's entry in your claims list and as the title of its management view. It does not change the claim boundaries, owner, trust entries, Capacity cost, or settings.

Renaming is owner-only. Trusted players and Managers can view Claim Info but cannot start rename mode.

## Continue Learning

- [Manage a Claim](managing-a-claim.md)
- [Custom Claim Icons](custom-claim-icons.md)
- [Claims Overview](../claims.md)
