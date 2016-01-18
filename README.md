# ECJTU-CERT-API

## Overview
To make our school life better,we're making the data available for the 3rd-party platforms.

## Items
Name | Path 
----------|-----------
JWXT Verification Code Recognition | ```./jwxt/verificationCodeRecg.php```

## Items Detail
Param | Optional | Type | Description
----------|-----|---------|--------------------
**codeString** | False | Base64Encode String | Base64 encoded PNG pixel

###Usage
```
http://api.gorgiaxx.com/ecjtu/verificationCodeRecg.php
```
####Post Data
```
codeString=iVBORw0KGgoAAAANSUhEUgAAAHgAAAAjCAIAAADQT1mxAAADMklEQVR42u3avYpUQRAF4JPJRj6BkWJm4CMoKMhmJmLgC6hgZKqgiaEmooKBgYmisaxgtBtopqCiBg6uJiKYCWY2NBZNdXd1VXXfu9fBpliGmcsw882Z6p9Z/P4/ZhkwXIq3awxx4fGz1ttfKYhWA6CTp7u0ZsRN5ZkSfWT7RSjjh3Ej3ri7cRF4GP4u5SuMp6Yg70HriNypOHAqvyyYpvVPt4u9gQ7j6+17oUic0N2yW9+vhRoGd3yblaZdfPt1rlZ0/aczP1lNCB2VQ6WyecytykOgc+K0BMpUszZyZQc3rMqhirG1ipOyDC0bxZKVKdrAFUe7EJRN1hI0xTZVjonWtPKIDuyTlUP1xI3FWbjfsboQQK3WaM5jTLkJ3Yw5U2aJBj74mobpM+hUZhdooeV5rAeaiTPcIT26Pe91Qzev6W0dwPsUtweaZZm5H3xwJ5T12c7evByrsRmZHlpjDeUyYxS0sOog7s2tlz5x5h478kDod7sfa9cAO07onLUfWg54bOXBGjgfrYFXjqdl7qOgc+UxiZ4TOp88A7c118XNCCmTO/DGMRnKyn7ooulAaOCEPBnmm0/HrrqY5Vqf6VneOaFroMX7d3fuK1h/+HaGMdelM5ZNvbLcNGT35m7FAA1cV8a2+BBwQGPdswUP1nGSFDLONiPu5TOJh14R24WM60y03ByER33W+nV0sE5bNmssbL/Xs0lh8x651/LbC62pOaFZtIXN50BlTZ+ZG7poDXwZfnqXWrN2Eaz7iQVlYarUzKvDoB259m3Bo3UebVL2LVeEzYhyoS2vZJzn0bVhsnafdcR+nXIXs6xfI/qWyf7Tu+VDU7uguTFYNzsGsFETl9tFzXrwebQDGljpra3QbHVB1pqDf/oYUvFmRx516t8LDbzuyTVBA5+tysXFnAba2liGKLehgWO+LbjGWplo+ZcRNzRDBw4J4rP+OGsa7u2iMsjC8J1uF1flA8dU0Kk18MR45HTLrZxy97x496lWA/rwo6tUS8j1PP+m5Y45cHpAoidCn7RdzCne2zqAk0t4M4tV/qv0fPIeDRydmnjhygudDNcpyOsD3fd13r/8F/kHmc05s0D+ywMAAAAASUVORK5CYII=
```
