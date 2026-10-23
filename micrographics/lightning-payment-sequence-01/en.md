# BD-V-059-01 Lightning payment sequence

## Alt text

A Lightning payment in six steps: the receiver creates a request, the sender scans it, checks recipient, amount, unit, expiry and fee, approves, the payment routes, and both wallets show the result. Each wallet may be custodial or self-custodial, and a failed or expired payment starts again with a new request.

## Texts

### boundary

Know whether each wallet is custodial or self-custodial.

### s1-title

Create the request

### s1-text

The receiver creates a payment request.

### s2-title

Scan the request

### s2-text

The sender scans or copies it.

### s3-title

Verify the details

### s3-text

Check recipient, amount, unit, expiry and fee.

### s4-title

Approve the payment

### s4-text

The sender approves it.

### s5-title

Route the payment

### s5-text

It travels across the Lightning Network.

### s6-title

Check the result

### s6-text

Both wallets show success or failure.

### loop

Failed or expired? Confirm on both wallets, then make a new request.
