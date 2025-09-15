> [!CAUTION]  
> ***Does not work yet***, but the classtables CRCs match. Custom clients can join hl2 vanilla servers.
> Vanilla HL2 clients can't join custom servers because HL2's engine has an older form of the SVC_VoiceInit netmessage, workaround soon.

> [!WARNING]  
> I tried to mostly ifdef things instead of cutting them straight out, but I do not guarantee a buildable client (especially for other mods)

# HL2 Dedicated Server (not HL2DM/MP, just straight HL2)

An attempt making a SDK 2013 based dedicated server compatible with 20th anniversary HL2

## Credits
- Valve  
- akabomb for a Rust framework that let me write a custom VSP for getting class metadata out of HL2
- Myknakryu for the dedicated server build script

## License

The SDK is licensed to users on a non-commercial basis under the [SOURCE 1 SDK LICENSE](LICENSE), which is contained in the [LICENSE](LICENSE) file in the root of the repository.
