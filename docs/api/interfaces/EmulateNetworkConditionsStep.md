[@puppeteer/replay](../README.md) / EmulateNetworkConditionsStep

# Interface: EmulateNetworkConditionsStep

## Hierarchy

- [`StepWithTarget`](Schema.StepWithTarget.md)

  ↳ **`EmulateNetworkConditionsStep`**

## Table of contents

### Properties

- [assertedEvents](EmulateNetworkConditionsStep.md#assertedevents)
- [download](EmulateNetworkConditionsStep.md#download)
- [latency](EmulateNetworkConditionsStep.md#latency)
- [target](EmulateNetworkConditionsStep.md#target)
- [timeout](EmulateNetworkConditionsStep.md#timeout)
- [type](EmulateNetworkConditionsStep.md#type)
- [upload](EmulateNetworkConditionsStep.md#upload)

## Properties

### assertedEvents

• `Optional` **assertedEvents**: [`NavigationEvent`](Schema.NavigationEvent.md)[]

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[assertedEvents](Schema.StepWithTarget.md#assertedevents)

#### Defined in

[Schema.ts:33](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L33)

---

### download

• **download**: `number`

#### Defined in

[Schema.ts:125](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L125)

---

### latency

• **latency**: `number`

#### Defined in

[Schema.ts:127](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L127)

---

### target

• `Optional` **target**: `string`

Defaults to main

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[target](Schema.StepWithTarget.md#target)

#### Defined in

[Schema.ts:40](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L40)

---

### timeout

• `Optional` **timeout**: `number`

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[timeout](Schema.StepWithTarget.md#timeout)

#### Defined in

[Schema.ts:32](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L32)

---

### type

• **type**: `"emulateNetworkConditions"`

#### Overrides

[StepWithTarget](Schema.StepWithTarget.md).[type](Schema.StepWithTarget.md#type)

#### Defined in

[Schema.ts:124](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L124)

---

### upload

• **upload**: `number`

#### Defined in

[Schema.ts:126](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L126)
