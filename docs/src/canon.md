# Canon

```@setup INFO
include(joinpath(Base.@__DIR__, "..", "docinfo.jl"))
info = DocInfo.Info()
```

## Physics

```@autodocs
Modules = [ Decapodes.Canon.Physics ]
Private = false
```

## Chemistry

```@autodocs
Modules = [ Decapodes.Canon.Chemistry ]
Private = false
```

## Biology

```@autodocs
Modules = [ Decapodes.Canon.Biology ]
Private = false
```

## Environment

```@autodocs
Modules = [ Decapodes.Canon.Environment ]
Private = false
```

```@example INFO
DocInfo.get_report(info) # hide
```
