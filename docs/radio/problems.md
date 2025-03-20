# 🚨 Common Problems

## The radio animations aren't working?

The radio animations aren't working? This is due to the default PMA voice being added by default. You need to remove it. To do so, add or edit it in your server.cfg:

```lua
setr voice_enableRadioAnim false
```