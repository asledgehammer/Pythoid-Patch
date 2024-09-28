### Version 6:
- Fixed critical flaw from allowing proper reloading of mods entirely.

### Version 5:
- Improvements & fixes to `pip` support.

### Version 4:
- Added experimental `pip` support by using `requirements.txt` in the root of the mod folder.
  > See: https://pip.pypa.io/en/latest/user_guide/#requirements-files for more info.

### Version 3:
- Fixed concurrency issue when adding or removing Python event-listeners while executing an event.
- Fixed `java2pi(Object[] args)` call in Events API causing `ClassCastException`.

### Version 2:
- Removed short-hand Global API calls. They should be called now using:
    `zombie.Lua.LuaManager.GlobalObject.apiCall()`

### Version 1:
- Initial release.