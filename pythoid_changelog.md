### Version 3:
- Fixed concurrency issue when adding or removing Python event-listeners while executing an event.
- Fixed `java2pi(Object[] args)` call in Events API causing `ClassCastException`.

### Version 2:
- Removed short-hand Global API calls. They should be called now using:
    `zombie.Lua.LuaManager.GlobalObject.apiCall()`

### Version 1:
- Initial release.