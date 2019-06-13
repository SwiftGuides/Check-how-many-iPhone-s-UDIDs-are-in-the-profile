# Check-what-UDIDs-are-in-Provisioning-profile-
Check how many iPhone's UDIDs are in the profile

Source :- https://stackoverflow.com/a/9778131/10422074

Run this code in Terminal

```
security cms -D -i /path/to/MyProfile.mobileprovision

```

It will show up the UDIDs of all devices which are added in the profile
