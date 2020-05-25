# SinunKirjastoUnify.DotnetLib
Unified dotnetLib for all dotnet libs 

# Include Dotnet CLI Tool 
When using cli it should work like `dotnet new netlib` 

# .NET Libraries
- netlib win 
- netlib android
- netlib ios
- netlib tizen
- netlib embedded
- netlib iot
- netlib sensors
- netlib razor
- netlib blazor
- netlib macos
- netlib linux
- netlib xr
- netlib vr
- netlib ar

so basically netlib for everything what can be consider as library 
and netlib itself can contain base for projections, templates and so on for example what then shared framework can use

# netlib extensions 
To add addional features for MSBuild 
this can be like `<TargetframeworkGroup> net5</TargetframeworkGroup>` what then collect things from that major dotnet version for example
so with `<PropertyGroup>` you can then target multiple version of dotnet

# NETLib to Follow main unified Dotnet journey

when new Dotnet release happen this can be then use line new version if user want to get new bits from major dotnet still keep flexible for backward compatible and make new things what can be implemented to major dotnet.