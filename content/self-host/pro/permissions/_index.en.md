---
title: Permission Control
weight: 15
---


## Device access permissions
There are two ways to associate a device with a user:
- Via console device page
- Log in to the specified user account on the client side

The following two situations will prevent the device from being accessed:
- Make device `disabled` in console devices page
- Make user `disable` in console user page

The associated device can only be accessed by the devices of the same user or user group, or in correct cross-group settings.

## Cross group settings

Please go to group page in the web console, click on `Edit` to edit cross group settings as below.

Your modifications to `Access with other groups` take effect immediately without requiring you to click the `OK` button.

Both `Can access to` and `Can be accessed from` serve almost the same function, we provide both options for your convenience. However, this may cause some confusion.

![](/docs/en/self-host/pro/permissions/images/crossgrp.png)