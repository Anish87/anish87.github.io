---
title: Anish's SqMod Wiki
description: This is Anish's custom SqMod wiki.
---
# SqMod (Squirrel Module) by S.L.C.
The VC:MP Squirrel Module is a plugin that can be loaded by the VC:MP server to provide a user the ability to script behavior into his server using the Squirrel scripting language. The goal of this plugin is to provide high-end features to the scripter and targets large scale game-mods. This is not an official module and requires a significant amount of programming knowledge in order to be used properly.

## Wiki Content
* [Constants](#constants)
* [Base Types](#base-types)
* [Entity Types](#entity-types)
* [Entity Algorithms](#entity-algorithms)
* [Modules](#modules)
* [Misc Types](#miscellaneous-types)

---
## Constants
* `enum` [SqMod](Enumerations/Enum.SqMod)
* `enum` [SqArchitecture](Enumerations/Enum.SqArchitecture)
* `enum` [SqPlatform](Enumerations/Enum.SqPlatform)
* `enum` [SqEvent](Enumerations/Enum.SqEvent)
* `enum` [SqCreate](Enumerations/Enum.SqCreate)
* `enum` [SqDestroy](Enumerations/Enum.SqDestroy)
* `enum` [SqServerError](Enumerations/Enum.SqServerError)
* `enum` [SqEntityPool](Enumerations/Enum.SqEntityPool)
* `enum` [SqPlayerUpdate](Enumerations/Enum.SqPlayerUpdate)
* `enum` [SqVehicleUpdate](Enumerations/Enum.SqVehicleUpdate)
* `enum` [SqPlayerVehicle](Enumerations/Enum.SqPlayerVehicle)
* `enum` [SqVehicleSync](Enumerations/Enum.SqVehicleSync)
* `enum` [SqPartReason](Enumerations/Enum.SqPartReason)
* `enum` [SqServerOption](Enumerations/Enum.SqServerOption)
* `enum` [SqPlayerOption](Enumerations/Enum.SqPlayerOption)
* `enum` [SqVehicleOption](Enumerations/Enum.SqVehicleOption)
* `enum` [SqPickupOption](Enumerations/Enum.SqPickupOption)
* `enum` [SqBodyPart](Enumerations/Enum.SqBodyPart)
* `enum` [SqPlayerState](Enumerations/Enum.SqPlayerState)
* `enum` [SqPlayerAction](Enumerations/Enum.SqPlayerAction)
* `enum` [SqWeather](Enumerations/Enum.SqWeather)
* `enum` [SqWep](Enumerations/Enum.SqWep)
* `enum` [SqVeh](Enumerations/Enum.SqVeh)
* `enum` [SqSkin](Enumerations/Enum.SqSkin)
* `enum` [SqKeyCode](Enumerations/Enum.SqKeyCode)
* `enum` [SqASCII](Enumerations/Enum.SqASCII)

## Base Types

* `class` [AABB](Class/Class.AABB)
* `class` [Circle](Class/Class.Circle)
* `class` [Color3](Class/Class.Color3)
* `class` [Color4](Class/Class.Color4)
* `class` [Quaternion](Class/Class.Quaternion)
* `class` [Sphere](Class/Class.Sphere)
* `class` [Vector2](Class/Class.Vector2)
* `class` [Vector2i](Class/Class.Vector2i)
* `class` [Vector3](Class/Class.Vector3)
* `class` [Vector4](Class/Class.Vector4)

## Entity Types

* `class` [SqBlip](Class/Class.SqBlip)
* `class` [SqCheckpoint](Class/Class.SqCheckpoint)
* `class` [SqKeybind](Class/Class.SqKeybind)
* `class` [SqObject](Class/Class.SqObject)
* `class` [SqPickup](Class/Class.SqPickup)
* `class` [SqPlayer](Class/Class.SqPlayer)
* `class` [SqVehicle](Class/Class.SqVehicle)

## Entity Algorithms

* `table` [SqCollect](Table.SqCollect)
* `table` [SqFind](Table.SqFind)
* `table` [SqForeach](Table.SqForeach)
* `table` [SqForeachEx](Table.SqForeachEx)
* `table` [SqCount](Table.SqCount)

## Modules
* `table` SqData
* `table` SqZMQ

## Miscellaneous Types

* `class` [SqSignalBase](Class/Class.SqSignalBase)
