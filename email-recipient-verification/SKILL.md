---
name: email-recipient-verification
description: Verify the recipient line of a consequential email against its primary source before sending, so an approved message does not bounce or go to the wrong address. Use for benefits, legal, medical, housing, money, or application mail.
---

# Email recipient verification

## When this applies

- Apply this check to any consequential send, such as benefits, legal, medical, housing, money or application mail, and to any send where a bounce or a wrong recipient would cost the user time or a deadline.
- Apply it even when the body text was approved word for word and the attachment was already checked.
- Skip it for routine low-stakes mail where the recipient comes from replying inside the original thread.

## Verify the recipient line against its source

- Find the recipient address in a primary source before sending, such as the official notice, the original thread or the contact record.
- Compare the address you are about to send to against that source character by character, including any prefix, hyphen or domain part.
- Never send to an address reconstructed from memory, from a similar address or from an earlier draft without that comparison.
- Check every address field the send carries, including copied recipients, and remove any address the source does not support.
- State the verified recipient back in the pre-send summary, so a mismatch is visible before the send rather than after a bounce.

## Verify the rest of the envelope

- Confirm the attachment file name matches the file the user approved for this recipient.
- Confirm the subject line names the same matter as the source document or thread.
- Send once, then read the Sent folder through the mail tool to confirm the service recorded the verified recipients.

## Handle a bounce or a wrong address

- Treat a bounce as a failed send, not a delivered message, and say so plainly in the first sentence of the report.
- Re-verify the correct address from the primary source before resending, and change nothing else in an approved body without the user seeing it.
- Resend only after the new recipient line passes the character-by-character check, and confirm the resend in the Sent folder.

## Tools this works with

- Any mail tool that can search threads, look up contacts, send, and read the Sent folder (Gmail, Outlook, or similar).

## Alternatives for better results

- Reply inside the original thread when one exists, because the thread already carries the verified address.
- Ask the user to confirm only the recipient line when two similar official addresses both appear in the record and the primary source does not settle which one governs.
