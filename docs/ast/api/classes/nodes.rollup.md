[@sequeljs/ast](../README.md) / [Exports](../modules.md) /
[Nodes](../modules/nodes.md) / RollUp

# Class: RollUp

[Nodes](../modules/nodes.md).RollUp

## Hierarchy

- [_Unary_](nodes.unary.md)<[_GroupingElement_](nodes.groupingelement.md) \|
  [_Visitable_](../modules/visitors.md#visitable)[]\>

  ↳ **RollUp**

## Table of contents

### Constructors

- [constructor](nodes.rollup.md#constructor)

### Properties

- [expr](nodes.rollup.md#expr)

### Accessors

- [value](nodes.rollup.md#value)

### Methods

- [add](nodes.rollup.md#add)
- [and](nodes.rollup.md#and)
- [as](nodes.rollup.md#as)
- [asc](nodes.rollup.md#asc)
- [average](nodes.rollup.md#average)
- [between](nodes.rollup.md#between)
- [bitwiseAnd](nodes.rollup.md#bitwiseand)
- [bitwiseNot](nodes.rollup.md#bitwisenot)
- [bitwiseOr](nodes.rollup.md#bitwiseor)
- [bitwiseShiftLeft](nodes.rollup.md#bitwiseshiftleft)
- [bitwiseShiftRight](nodes.rollup.md#bitwiseshiftright)
- [bitwiseXor](nodes.rollup.md#bitwisexor)
- [coalesce](nodes.rollup.md#coalesce)
- [concat](nodes.rollup.md#concat)
- [count](nodes.rollup.md#count)
- [createAnd](nodes.rollup.md#createand)
- [createFalse](nodes.rollup.md#createfalse)
- [createJoin](nodes.rollup.md#createjoin)
- [createOn](nodes.rollup.md#createon)
- [createStringJoin](nodes.rollup.md#createstringjoin)
- [createTableAlias](nodes.rollup.md#createtablealias)
- [createTrue](nodes.rollup.md#createtrue)
- [desc](nodes.rollup.md#desc)
- [divide](nodes.rollup.md#divide)
- [doesNotMatch](nodes.rollup.md#doesnotmatch)
- [doesNotMatchAll](nodes.rollup.md#doesnotmatchall)
- [doesNotMatchAny](nodes.rollup.md#doesnotmatchany)
- [doesNotMatchRegexp](nodes.rollup.md#doesnotmatchregexp)
- [eq](nodes.rollup.md#eq)
- [eqAll](nodes.rollup.md#eqall)
- [eqAny](nodes.rollup.md#eqany)
- [extract](nodes.rollup.md#extract)
- [grouping](nodes.rollup.md#grouping)
- [groupingAll](nodes.rollup.md#groupingall)
- [groupingAny](nodes.rollup.md#groupingany)
- [gt](nodes.rollup.md#gt)
- [gtAll](nodes.rollup.md#gtall)
- [gtAny](nodes.rollup.md#gtany)
- [gteq](nodes.rollup.md#gteq)
- [gteqAll](nodes.rollup.md#gteqall)
- [gteqAny](nodes.rollup.md#gteqany)
- [inAll](nodes.rollup.md#inall)
- [inAny](nodes.rollup.md#inany)
- [inVal](nodes.rollup.md#inval)
- [isDistinctFrom](nodes.rollup.md#isdistinctfrom)
- [isInfinity](nodes.rollup.md#isinfinity)
- [isNotDistinctFrom](nodes.rollup.md#isnotdistinctfrom)
- [isOpenEnded](nodes.rollup.md#isopenended)
- [isUnboundable](nodes.rollup.md#isunboundable)
- [lower](nodes.rollup.md#lower)
- [lt](nodes.rollup.md#lt)
- [ltAll](nodes.rollup.md#ltall)
- [ltAny](nodes.rollup.md#ltany)
- [lteq](nodes.rollup.md#lteq)
- [lteqAll](nodes.rollup.md#lteqall)
- [lteqAny](nodes.rollup.md#lteqany)
- [matches](nodes.rollup.md#matches)
- [matchesAll](nodes.rollup.md#matchesall)
- [matchesAny](nodes.rollup.md#matchesany)
- [matchesRegexp](nodes.rollup.md#matchesregexp)
- [maximum](nodes.rollup.md#maximum)
- [minimum](nodes.rollup.md#minimum)
- [multiply](nodes.rollup.md#multiply)
- [not](nodes.rollup.md#not)
- [notBetween](nodes.rollup.md#notbetween)
- [notEq](nodes.rollup.md#noteq)
- [notEqAll](nodes.rollup.md#noteqall)
- [notEqAny](nodes.rollup.md#noteqany)
- [notInAll](nodes.rollup.md#notinall)
- [notInAny](nodes.rollup.md#notinany)
- [notInVal](nodes.rollup.md#notinval)
- [or](nodes.rollup.md#or)
- [quotedArray](nodes.rollup.md#quotedarray)
- [quotedNode](nodes.rollup.md#quotednode)
- [subtract](nodes.rollup.md#subtract)
- [sum](nodes.rollup.md#sum)
- [toSQL](nodes.rollup.md#tosql)
- [when](nodes.rollup.md#when)

## Constructors

### constructor

\+ **new RollUp**(`expr`: [_GroupingElement_](nodes.groupingelement.md) \|
[_Visitable_](../modules/visitors.md#visitable)[]): [_RollUp_](nodes.rollup.md)

#### Parameters:

| Name   | Type                                                                                               |
| ------ | -------------------------------------------------------------------------------------------------- |
| `expr` | [_GroupingElement_](nodes.groupingelement.md) \| [_Visitable_](../modules/visitors.md#visitable)[] |

**Returns:** [_RollUp_](nodes.rollup.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/nodes/Unary.ts:12](https://github.com/sequeljs/ast/blob/8de61b1/src/nodes/Unary.ts#L12)

## Properties

### expr

• **expr**: [_GroupingElement_](nodes.groupingelement.md) \|
[_Visitable_](../modules/visitors.md#visitable)[]

Inherited from: [Unary](nodes.unary.md).[expr](nodes.unary.md#expr)

Defined in:
[src/nodes/Unary.ts:8](https://github.com/sequeljs/ast/blob/8de61b1/src/nodes/Unary.ts#L8)

## Accessors

### value

• **value**(): T

**Returns:** T

Defined in:
[src/nodes/Unary.ts:10](https://github.com/sequeljs/ast/blob/8de61b1/src/nodes/Unary.ts#L10)

## Methods

### add

▸ **add**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:14](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L14)

---

### and

▸ **and**(`right`: _any_): [_And_](nodes.and.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `right` | _any_ |

**Returns:** [_And_](nodes.and.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/NodeMethods.ts:11](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/NodeMethods.ts#L11)

---

### as

▸ **as**(`other`: _string_ \| [_SQLLiteral_](nodes.sqlliteral.md)):
[_As_](nodes.as.md)

#### Parameters:

| Name    | Type                                            |
| ------- | ----------------------------------------------- |
| `other` | _string_ \| [_SQLLiteral_](nodes.sqlliteral.md) |

**Returns:** [_As_](nodes.as.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/AliasPredication.ts:5](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/AliasPredication.ts#L5)

---

### asc

▸ **asc**(): [_Ascending_](nodes.ascending.md)

**Returns:** [_Ascending_](nodes.ascending.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/OrderPredications.ts:7](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/OrderPredications.ts#L7)

---

### average

▸ **average**(): [_Avg_](nodes.avg.md)

**Returns:** [_Avg_](nodes.avg.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:9](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L9)

---

### between

▸ **between**(`begin`: _number_ \| [_BindParam_](nodes.bindparam.md) \|
[_Quoted_](nodes.quoted.md), `end`: _number_ \|
[_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md), `inclusive?`:
_boolean_): [_GreaterThanOrEqual_](nodes.greaterthanorequal.md) \|
[_LessThan_](nodes.lessthan.md) \| [_LessThanOrEqual_](nodes.lessthanorequal.md)
\| [_NotIn_](nodes.notin.md) \| [_And_](nodes.and.md) \|
[_Between_](nodes.between.md)

#### Parameters:

| Name        | Type                                                                         | Default value |
| ----------- | ---------------------------------------------------------------------------- | ------------- |
| `begin`     | _number_ \| [_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md) | -             |
| `end`       | _number_ \| [_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md) | -             |
| `inclusive` | _boolean_                                                                    | true          |

**Returns:** [_GreaterThanOrEqual_](nodes.greaterthanorequal.md) \|
[_LessThan_](nodes.lessthan.md) \| [_LessThanOrEqual_](nodes.lessthanorequal.md)
\| [_NotIn_](nodes.notin.md) \| [_And_](nodes.and.md) \|
[_Between_](nodes.between.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:257](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L257)

---

### bitwiseAnd

▸ **bitwiseAnd**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:18](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L18)

---

### bitwiseNot

▸ **bitwiseNot**(): [_BitwiseNot_](nodes.bitwisenot.md)

**Returns:** [_BitwiseNot_](nodes.bitwisenot.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:22](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L22)

---

### bitwiseOr

▸ **bitwiseOr**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:26](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L26)

---

### bitwiseShiftLeft

▸ **bitwiseShiftLeft**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:30](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L30)

---

### bitwiseShiftRight

▸ **bitwiseShiftRight**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:34](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L34)

---

### bitwiseXor

▸ **bitwiseXor**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:38](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L38)

---

### coalesce

▸ **coalesce**(...`exprs`: _any_[]):
[_NamedSQLFunction_](nodes.namedsqlfunction.md)

#### Parameters:

| Name       | Type    |
| ---------- | ------- |
| `...exprs` | _any_[] |

**Returns:** [_NamedSQLFunction_](nodes.namedsqlfunction.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:22](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L22)

---

### concat

▸ **concat**(`other`: _any_): [_Concat_](nodes.concat.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Concat_](nodes.concat.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/ConcatPredication.ts:4](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/ConcatPredication.ts#L4)

---

### count

▸ **count**(`distinct?`: _boolean_): [_Count_](nodes.count.md)

#### Parameters:

| Name       | Type      | Default value |
| ---------- | --------- | ------------- |
| `distinct` | _boolean_ | false         |

**Returns:** [_Count_](nodes.count.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:13](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L13)

---

### createAnd

▸ **createAnd**(`clauses`: _any_[]): [_And_](nodes.and.md)

#### Parameters:

| Name      | Type    |
| --------- | ------- |
| `clauses` | _any_[] |

**Returns:** [_And_](nodes.and.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:26](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L26)

---

### createFalse

▸ **createFalse**(): [_False_](nodes.false.md)

**Returns:** [_False_](nodes.false.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:30](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L30)

---

### createJoin

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md)):
[_InnerJoin_](nodes.innerjoin.md)

#### Parameters:

| Name | Type                                                                                                                    |
| ---- | ----------------------------------------------------------------------------------------------------------------------- |
| `to` | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |

**Returns:** [_InnerJoin_](nodes.innerjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:34](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L34)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_): [_InnerJoin_](nodes.innerjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |

**Returns:** [_InnerJoin_](nodes.innerjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:35](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L35)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_, `Klass`: _typeof_
[_FullOuterJoin_](nodes.fullouterjoin.md)):
[_FullOuterJoin_](nodes.fullouterjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |
| `Klass`      | _typeof_ [_FullOuterJoin_](nodes.fullouterjoin.md)                                                                      |

**Returns:** [_FullOuterJoin_](nodes.fullouterjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:39](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L39)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_, `Klass`: _typeof_ [_InnerJoin_](nodes.innerjoin.md)):
[_InnerJoin_](nodes.innerjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |
| `Klass`      | _typeof_ [_InnerJoin_](nodes.innerjoin.md)                                                                              |

**Returns:** [_InnerJoin_](nodes.innerjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:44](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L44)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_, `Klass`: _typeof_ [_OuterJoin_](nodes.outerjoin.md)):
[_OuterJoin_](nodes.outerjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |
| `Klass`      | _typeof_ [_OuterJoin_](nodes.outerjoin.md)                                                                              |

**Returns:** [_OuterJoin_](nodes.outerjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:49](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L49)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_, `Klass`: _typeof_
[_RightOuterJoin_](nodes.rightouterjoin.md)):
[_RightOuterJoin_](nodes.rightouterjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |
| `Klass`      | _typeof_ [_RightOuterJoin_](nodes.rightouterjoin.md)                                                                    |

**Returns:** [_RightOuterJoin_](nodes.rightouterjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:54](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L54)

▸ **createJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md),
`constraint`: _any_, `Klass`: _typeof_ [_StringJoin_](nodes.stringjoin.md)):
[_StringJoin_](nodes.stringjoin.md)

#### Parameters:

| Name         | Type                                                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| `to`         | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |
| `constraint` | _any_                                                                                                                   |
| `Klass`      | _typeof_ [_StringJoin_](nodes.stringjoin.md)                                                                            |

**Returns:** [_StringJoin_](nodes.stringjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:59](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L59)

---

### createOn

▸ **createOn**(`expr`: _any_): [_On_](nodes.on.md)

#### Parameters:

| Name   | Type  |
| ------ | ----- |
| `expr` | _any_ |

**Returns:** [_On_](nodes.on.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:72](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L72)

---

### createStringJoin

▸ **createStringJoin**(`to`: _null_ \| _string_ \| [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md)):
[_StringJoin_](nodes.stringjoin.md)

#### Parameters:

| Name | Type                                                                                                                    |
| ---- | ----------------------------------------------------------------------------------------------------------------------- |
| `to` | _null_ \| _string_ \| [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_SQLLiteral_](nodes.sqlliteral.md) |

**Returns:** [_StringJoin_](nodes.stringjoin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:76](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L76)

---

### createTableAlias

▸ **createTableAlias**(`relation`: [_Table_](table.md) \|
[_TableAlias_](nodes.tablealias.md) \| [_Grouping_](nodes.grouping.md), `name`:
_string_ \| [_SQLLiteral_](nodes.sqlliteral.md)):
[_TableAlias_](nodes.tablealias.md)

#### Parameters:

| Name       | Type                                                                                          |
| ---------- | --------------------------------------------------------------------------------------------- |
| `relation` | [_Table_](table.md) \| [_TableAlias_](nodes.tablealias.md) \| [_Grouping_](nodes.grouping.md) |
| `name`     | _string_ \| [_SQLLiteral_](nodes.sqlliteral.md)                                               |

**Returns:** [_TableAlias_](nodes.tablealias.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:80](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L80)

---

### createTrue

▸ **createTrue**(): [_True_](nodes.true.md)

**Returns:** [_True_](nodes.true.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:87](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L87)

---

### desc

▸ **desc**(): [_Descending_](nodes.descending.md)

**Returns:** [_Descending_](nodes.descending.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/OrderPredications.ts:11](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/OrderPredications.ts#L11)

---

### divide

▸ **divide**(`other`: _any_): [_Division_](nodes.division.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Division_](nodes.division.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:42](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L42)

---

### doesNotMatch

▸ **doesNotMatch**(`other`: _any_, `escape?`: _any_, `caseSensitive?`:
_boolean_): [_DoesNotMatch_](nodes.doesnotmatch.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `other`         | _any_     | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_DoesNotMatch_](nodes.doesnotmatch.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:57](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L57)

---

### doesNotMatchAll

▸ **doesNotMatchAll**(`others`: _any_, `escape?`: _any_, `caseSensitive?`:
_boolean_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `others`        | _any_     | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:65](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L65)

---

### doesNotMatchAny

▸ **doesNotMatchAny**(`others`: _any_, `escape?`: _any_, `caseSensitive?`:
_boolean_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `others`        | _any_     | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:78](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L78)

---

### doesNotMatchRegexp

▸ **doesNotMatchRegexp**(`other`: _any_, `caseSensitive?`: _boolean_):
[_NotRegexp_](nodes.notregexp.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `other`         | _any_     | -             |
| `caseSensitive` | _boolean_ | true          |

**Returns:** [_NotRegexp_](nodes.notregexp.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:91](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L91)

---

### eq

▸ **eq**(`other`: _any_): [_Equality_](nodes.equality.md)<_any_, _any_\>

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Equality_](nodes.equality.md)<_any_, _any_\>

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:95](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L95)

---

### eqAll

▸ **eqAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:99](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L99)

---

### eqAny

▸ **eqAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:103](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L103)

---

### extract

▸ **extract**(`field`: _any_): [_Extract_](nodes.extract.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `field` | _any_ |

**Returns:** [_Extract_](nodes.extract.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:17](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L17)

---

### grouping

▸ **grouping**(`expr`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name   | Type  |
| ------ | ----- |
| `expr` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:91](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L91)

---

### groupingAll

▸ `Protected`**groupingAll**(`method`: (`expr`: _any_, ...`extras`: _any_[]) =>
_any_, `others`: _any_[], ...`extras`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name        | Type                                           |
| ----------- | ---------------------------------------------- |
| `method`    | (`expr`: _any_, ...`extras`: _any_[]) => _any_ |
| `others`    | _any_[]                                        |
| `...extras` | _any_[]                                        |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:25](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L25)

---

### groupingAny

▸ `Protected`**groupingAny**(`method`: (`expr`: _any_, ...`extras`: _any_[]) =>
_any_, `others`: _any_[], ...`extras`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name        | Type                                           |
| ----------- | ---------------------------------------------- |
| `method`    | (`expr`: _any_, ...`extras`: _any_[]) => _any_ |
| `others`    | _any_[]                                        |
| `...extras` | _any_[]                                        |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:35](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L35)

---

### gt

▸ **gt**(`other`: _any_): [_GreaterThan_](nodes.greaterthan.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_GreaterThan_](nodes.greaterthan.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:107](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L107)

---

### gtAll

▸ **gtAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:111](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L111)

---

### gtAny

▸ **gtAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:115](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L115)

---

### gteq

▸ **gteq**(`other`: _any_): [_GreaterThanOrEqual_](nodes.greaterthanorequal.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_GreaterThanOrEqual_](nodes.greaterthanorequal.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:119](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L119)

---

### gteqAll

▸ **gteqAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:123](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L123)

---

### gteqAny

▸ **gteqAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:127](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L127)

---

### inAll

▸ **inAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:143](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L143)

---

### inAny

▸ **inAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:147](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L147)

---

### inVal

▸ **inVal**(`other`: _any_): [_In_](nodes.in.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_In_](nodes.in.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:131](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L131)

---

### isDistinctFrom

▸ **isDistinctFrom**(`other`: _any_):
[_IsDistinctFrom_](nodes.isdistinctfrom.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_IsDistinctFrom_](nodes.isdistinctfrom.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:155](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L155)

---

### isInfinity

▸ `Protected`**isInfinity**(`value`: _any_): _boolean_

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `value` | _any_ |

**Returns:** _boolean_

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:45](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L45)

---

### isNotDistinctFrom

▸ **isNotDistinctFrom**(`other`: _any_):
[_IsNotDistinctFrom_](nodes.isnotdistinctfrom.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_IsNotDistinctFrom_](nodes.isnotdistinctfrom.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:151](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L151)

---

### isOpenEnded

▸ `Protected`**isOpenEnded**(`value`: _any_): _boolean_

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `value` | _any_ |

**Returns:** _boolean_

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:49](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L49)

---

### isUnboundable

▸ `Protected`**isUnboundable**(`value`: _any_): _boolean_

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `value` | _any_ |

**Returns:** _boolean_

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:53](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L53)

---

### lower

▸ **lower**(`column`: _any_): [_NamedSQLFunction_](nodes.namedsqlfunction.md)

#### Parameters:

| Name     | Type  |
| -------- | ----- |
| `column` | _any_ |

**Returns:** [_NamedSQLFunction_](nodes.namedsqlfunction.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/FactoryMethods.ts:95](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/FactoryMethods.ts#L95)

---

### lt

▸ **lt**(`other`: _any_): [_LessThan_](nodes.lessthan.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_LessThan_](nodes.lessthan.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:159](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L159)

---

### ltAll

▸ **ltAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:163](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L163)

---

### ltAny

▸ **ltAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:167](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L167)

---

### lteq

▸ **lteq**(`other`: _any_): [_LessThanOrEqual_](nodes.lessthanorequal.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_LessThanOrEqual_](nodes.lessthanorequal.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:171](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L171)

---

### lteqAll

▸ **lteqAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:175](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L175)

---

### lteqAny

▸ **lteqAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:179](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L179)

---

### matches

▸ **matches**(`other`: _any_, `escape?`: _any_, `caseSensitive?`: _boolean_):
[_Matches_](nodes.matches.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `other`         | _any_     | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_Matches_](nodes.matches.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:183](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L183)

---

### matchesAll

▸ **matchesAll**(`others`: _any_[], `escape?`: _any_, `caseSensitive?`:
_boolean_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `others`        | _any_[]   | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:187](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L187)

---

### matchesAny

▸ **matchesAny**(`others`: _any_[], `escape?`: _any_, `caseSensitive?`:
_boolean_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `others`        | _any_[]   | -             |
| `escape`        | _any_     | null          |
| `caseSensitive` | _boolean_ | false         |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:200](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L200)

---

### matchesRegexp

▸ **matchesRegexp**(`other`: _any_, `caseSensitive?`: _boolean_):
[_Regexp_](nodes.regexp.md)

#### Parameters:

| Name            | Type      | Default value |
| --------------- | --------- | ------------- |
| `other`         | _any_     | -             |
| `caseSensitive` | _boolean_ | true          |

**Returns:** [_Regexp_](nodes.regexp.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:213](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L213)

---

### maximum

▸ **maximum**(): [_Max_](nodes.max.md)

**Returns:** [_Max_](nodes.max.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:21](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L21)

---

### minimum

▸ **minimum**(): [_Min_](nodes.min.md)

**Returns:** [_Min_](nodes.min.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:25](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L25)

---

### multiply

▸ **multiply**(`other`: _any_): [_Multiplication_](nodes.multiplication.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Multiplication_](nodes.multiplication.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:46](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L46)

---

### not

▸ **not**(): [_Not_](nodes.not.md)

**Returns:** [_Not_](nodes.not.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/NodeMethods.ts:15](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/NodeMethods.ts#L15)

---

### notBetween

▸ **notBetween**(`begin`: _number_ \| [_BindParam_](nodes.bindparam.md) \|
[_Quoted_](nodes.quoted.md), `end`: _number_ \|
[_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md), `inclusive?`:
_boolean_): [_Grouping_](nodes.grouping.md) \|
[_GreaterThan_](nodes.greaterthan.md) \|
[_GreaterThanOrEqual_](nodes.greaterthanorequal.md) \| [_In_](nodes.in.md) \|
[_LessThan_](nodes.lessthan.md)

#### Parameters:

| Name        | Type                                                                         | Default value |
| ----------- | ---------------------------------------------------------------------------- | ------------- |
| `begin`     | _number_ \| [_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md) | -             |
| `end`       | _number_ \| [_BindParam_](nodes.bindparam.md) \| [_Quoted_](nodes.quoted.md) | -             |
| `inclusive` | _boolean_                                                                    | true          |

**Returns:** [_Grouping_](nodes.grouping.md) \|
[_GreaterThan_](nodes.greaterthan.md) \|
[_GreaterThanOrEqual_](nodes.greaterthanorequal.md) \| [_In_](nodes.in.md) \|
[_LessThan_](nodes.lessthan.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:292](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L292)

---

### notEq

▸ **notEq**(`other`: _any_): [_NotEqual_](nodes.notequal.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_NotEqual_](nodes.notequal.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:217](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L217)

---

### notEqAll

▸ **notEqAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:221](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L221)

---

### notEqAny

▸ **notEqAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:225](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L225)

---

### notInAll

▸ **notInAll**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:241](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L241)

---

### notInAny

▸ **notInAny**(`others`: _any_[]): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:245](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L245)

---

### notInVal

▸ **notInVal**(`other`: _any_): [_NotIn_](nodes.notin.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_NotIn_](nodes.notin.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:229](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L229)

---

### or

▸ **or**<T\>(`right`: T): [_Grouping_](nodes.grouping.md)

#### Type parameters:

| Name | Type                                            |
| ---- | ----------------------------------------------- |
| `T`  | [_Visitable_](../modules/visitors.md#visitable) |

#### Parameters:

| Name    | Type |
| ------- | ---- |
| `right` | T    |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/NodeMethods.ts:19](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/NodeMethods.ts#L19)

---

### quotedArray

▸ **quotedArray**(`others`: _any_[]): _any_[]

#### Parameters:

| Name     | Type    |
| -------- | ------- |
| `others` | _any_[] |

**Returns:** _any_[]

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:253](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L253)

---

### quotedNode

▸ **quotedNode**(`other`: _any_): _any_

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** _any_

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Predications.ts:249](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Predications.ts#L249)

---

### subtract

▸ **subtract**(`other`: _any_): [_Grouping_](nodes.grouping.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Grouping_](nodes.grouping.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Math.ts:50](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Math.ts#L50)

---

### sum

▸ **sum**(): [_Sum_](nodes.sum.md)

**Returns:** [_Sum_](nodes.sum.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/Expressions.ts:29](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/Expressions.ts#L29)

---

### toSQL

▸ **toSQL**(`engine?`: _null_ \|
[_Engine_](../interfaces/interfaces.engine.md)): _any_

#### Parameters:

| Name     | Type                                                     | Default value |
| -------- | -------------------------------------------------------- | ------------- |
| `engine` | _null_ \| [_Engine_](../interfaces/interfaces.engine.md) | ...           |

**Returns:** _any_

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/nodes/Node.ts:16](https://github.com/sequeljs/ast/blob/8de61b1/src/nodes/Node.ts#L16)

---

### when

▸ **when**(`other`: _any_): [_Case_](nodes.case.md)

#### Parameters:

| Name    | Type  |
| ------- | ----- |
| `other` | _any_ |

**Returns:** [_Case_](nodes.case.md)

Inherited from: [Unary](nodes.unary.md)

Defined in:
[src/mixins/WhenPredication.ts:5](https://github.com/sequeljs/ast/blob/8de61b1/src/mixins/WhenPredication.ts#L5)