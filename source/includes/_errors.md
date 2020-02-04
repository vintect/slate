# Errors

<aside class="notice">
This error section is stored in a separate file in <code>includes/_errors.md</code>. Slate allows you to optionally separate out your docs into many files...just save them to the <code>includes</code> folder and add them to the top of your <code>index.md</code>'s frontmatter. Files are included in the order listed.
</aside>

The Kittn API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is wrong.
403 | Forbidden -- The kitten requested is hidden for administrators only.
404 | Not Found -- The specified kitten could not be found.
405 | Method Not Allowed -- You tried to access a kitten with an invalid method.
406 | Not Acceptable -- You requested a format that isn't json.
410 | Gone -- The kitten requested has been removed from our servers.
418 | I'm a teapot.
429 | Too Many Requests -- You're requesting too many kittens! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
601 | Invalid Token
612 | Abuse Request
613 | Invalid Email or Password
614 | INvalid Password
615 | Singin In Next 10 Minutes
616 | Email Already Used
617 | Invalid Verification Code
618 | Email Must Be Not Empty
619 | Password Must Be Not Empty
621 | User Has Been Banned
622 | User Inactive
637 | You Already Check-In, You Can Only Check-In Every 6 Hours In The Same Location
638 | You Cannot Check-In Yet, You Can Only Check-In Every 15 Minutes For Another Location
641 | DAL Error
642 | Database Connection Failed
651 | Wrong Request
654 | Review Already Exist
731 | Password Has Been Set
732 | Facebook Or Google Has Been Linked
733 | Account Expired
734 | Phone Number Already Used
745 | User Already Check-In In The Same Place
746 | User Already Check-In Sometimes Ago
807 | New Error
912 | Decrypt Failed
951 | Some Error Occourred In MRT Future