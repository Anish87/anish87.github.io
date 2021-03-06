# Description

Check if a slot with a specific environment was bound to the signal.

# Specifications

* **Aliases**:
```js
SqSignalBase.ExistsThis
```
* **Signature**:
```js
(environment);
```
* **Parameters**:
	* **_environment_** `object` *(optional) The object that represents the environment in the slot.*
* **Return**:
	* `integer` The number of times there was a match for the specified environment.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

If the environment parameter is not specified. The current root table will be used instead.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.ExistsFunc](Function.SqSignalBase.Exists)
* `function` [SqSignalBase.ExistsThis](Function.SqSignalBase.ExistsThis)

# References

> No references available.
