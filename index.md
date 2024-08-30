---
title: Anish's SqMod Wiki
description: This is Anish's custom SqMod wiki.
baseurl: ""
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
* `enum` [SqMod](Enumerations/SqMod)
* `enum` [SqArchitecture](Enumerations/SqArchitecture)
* `enum` [SqPlatform](Enumerations/SqPlatform)
* `enum` [SqEvent](Enumerations/SqEvent)
* `enum` [SqCreate](Enumerations/SqCreate)
* `enum` [SqDestroy](Enumerations/SqDestroy)
* `enum` [SqServerError](Enumerations/SqServerError)
* `enum` [SqEntityPool](Enumerations/SqEntityPool)
* `enum` [SqPlayerUpdate](Enumerations/SqPlayerUpdate)
* `enum` [SqVehicleUpdate](Enumerations/SqVehicleUpdate)
* `enum` [SqPlayerVehicle](Enumerations/SqPlayerVehicle)
* `enum` [SqVehicleSync](Enumerations/SqVehicleSync)
* `enum` [SqPartReason](Enumerations/SqPartReason)
* `enum` [SqServerOption](Enumerations/SqServerOption)
* `enum` [SqPlayerOption](Enumerations/SqPlayerOption)
* `enum` [SqVehicleOption](Enumerations/SqVehicleOption)
* `enum` [SqPickupOption](Enumerations/SqPickupOption)
* `enum` [SqBodyPart](Enumerations/SqBodyPart)
* `enum` [SqPlayerState](Enumerations/SqPlayerState)
* `enum` [SqPlayerAction](Enumerations/SqPlayerAction)
* `enum` [SqWeather](Enumerations/SqWeather)
* `enum` [SqWep](Enumerations/SqWep)
* `enum` [SqVeh](Enumerations/SqVeh)
* `enum` [SqSkin](Enumerations/SqSkin)
* `enum` [SqKeyCode](Enumerations/SqKeyCode)
* `enum` [SqASCII](Enumerations/SqASCII)

## Base Types

* `class` [AABB](Classes/AABB)
* `class` [Circle](Classes/Circle)
* `class` [Color3](Classes/Color3)
* `class` [Color4](Classes/Color4)
* `class` [Quaternion](Classes/Quaternion)
* `class` [Sphere](Classes/Sphere)
* `class` [Vector2](Classes/Vector2)
* `class` [Vector2i](Classes/Vector2i)
* `class` [Vector3](Classes/Vector3)
* `class` [Vector4](Classes/Vector4)

## Entity Types

* `class` [SqBlip](Classes/SqBlip)
* `class` [SqCheckpoint](Classes/SqCheckpoint)
* `class` [SqKeybind](Classes/SqKeybind)
* `class` [SqObject](Classes/SqObject)
* `class` [SqPickup](Classes/SqPickup)
* `class` [SqPlayer](Classes/SqPlayer)
* `class` [SqVehicle](Classes/SqVehicle)

## Entity Algorithms

* `table` [SqCollect](Tables/SqCollect)
* `table` [SqFind](Tables/SqFind)
* `table` [SqForeach](Tables/SqForeach)
* `table` [SqForeachEx](Tables/SqForeachEx)
* `table` [SqCount](Tables/SqCount)

## Modules
* `table` [SqData](Tables/SqData)
* `table` [SqZMQ](Tables/SqZMQ)
* `table` [SqCmd](Tables/SqCmd)
* `table` [SqLog](Tables/SqLog)

## Miscellaneous Types

* `class` [SqSignalBase](Classes/SqSignalBase)
