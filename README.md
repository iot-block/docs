### Token Swap Api

You can post form data with `itcAddress` and `ethAddress`, get a destroyAddress.

Url: `https://wallet.iotchain.io/v1/convert/bind`

Param: `itcAddress` and `ethAddress`

return: `destoryAddress`

example:

```bash
$ curl -d "itcAddress=0x0e2e0964a2e814e0331fedeb1d4a5b15495a66a1&ethAddress=0x0e2e0964a2e814e0331fedeb1d4a5b15495a66a1" https://wallet.iotchain.io/v1/convert/bind

{
    "code": 200,
    "data": {
        "convertId": 712,
        "itcAddress": "0x0e2e0964a2e814e0331fedeb1d4a5b15495a66a1",
        "ethAddress": "0x0e2e0964a2e814e0331fedeb1d4a5b15495a66a1",
        "destoryAddress": "0x0000000000000000000016109ef55f169252c462",
        "updateTime": "2019-08-08T07:54:41.000Z"
    },
    "msg": "success"
}
```
