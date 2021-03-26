# Description

Fast, efficient and flexible implementation of the [signals and slots](https://en.wikipedia.org/wiki/Signals_and_slots) concept. Used heavily throughout the plug-in to deliver events from the server as well as the plug-in itself. Some features or safeguards have been omitted for the sake of efficiency. However, the implementation is solid enough to deliver a good experience when dealing with events.

----

## Aliases:

* `class` SqSignalBase

## Meta-methods

* `function` [\_typename](Signals/Function.SqSignalBase._typename)
* `function` [\_tostring](Signals/Function.SqSignalBase._tostring)

## Properties

* `object` [Data](Property.SqSignalBase.Data)
* `string` [Name](Property.SqSignalBase.Name)
* `integer` [Slots](Property.SqSignalBase.Slots)
* `bool` [Empty](Property.SqSignalBase.Empty)

## Methods

* `function` [Connect](Signals/Function.SqSignalBase.Connect)
* `function` [ConnectOnce](Signals/Function.SqSignalBase.ConnectOnce)
* `function` [Exists](Signals/Function.SqSignalBase.Exists)
* `function` [Disconnect](Signals/Function.SqSignalBase.Disconnect)
* `function` [ExistsThis](Signals/Function.SqSignalBase.ExistsThis)
* `function` [ExistsFunc](Signals/Function.SqSignalBase.ExistsFunc)
* `function` [Count](Signals/Function.SqSignalBase.Count)
* `function` [CountThis](Signals/Function.SqSignalBase.CountThis)
* `function` [CountFunc](Signals/Function.SqSignalBase.CountFunc)
* `function` [Lead](Signals/Function.SqSignalBase.Lead)
* `function` [LeadThis](Signals/Function.SqSignalBase.LeadThis)
* `function` [LeadFunc](Signals/Function.SqSignalBase.LeadFunc)
* `function` [Tail](Signals/Function.SqSignalBase.Tail)
* `function` [TailThis](Signals/Function.SqSignalBase.TailThis)
* `function` [TailFunc](Signals/Function.SqSignalBase.TailFunc)
* `function` [Eliminate](Signals/Function.SqSignalBase.Eliminate)
* `function` [EliminateThis](Signals/Function.SqSignalBase.EliminateThis)
* `function` [EliminateFunc](Signals/Function.SqSignalBase.EliminateFunc)
* `function` [Emit](Signals/Function.SqSignalBase.Emit)
* `function` [Query](Signals/Function.SqSignalBase.Query)
* `function` [Consume](Signals/Function.SqSignalBase.Consume)
* `function` [Approve](Signals/Function.SqSignalBase.Approve)
* `function` [Request](Signals/Function.SqSignalBase.Request)
