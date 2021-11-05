# Verifying A Transaction

You should verify the details of the transaction prior to approving it. In order to do that, you will recreate the initial transaction and make sure the hashes match.

Navigate to Developer -> Extrinsics and prepare the transaction as if you were initializing it. Fill out all the relevant fields (be sure to use the correct function, see #1 below), but instead of signing and submitting it take note of the hash (#3) and encoded call string (#2). Make sure the hash matches the transaction before approving it.

If you are the last person to approve the transaction, or if it has already met the threshold, you can execute the transaction using the call string.

![](../.gitbook/assets/Screenshot\_20211020\_063827.png)

