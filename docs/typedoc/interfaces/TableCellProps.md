[@propra/react-pdf-table](../README.md) / [Exports](../modules.md) / TableCellProps

# Interface: TableCellProps

Whether to include borders or not.
Depending on the context some toggles will not have any effect.

## Hierarchy

- [`TableBorder`](TableBorder.md)

- `PropsWithChildren`

  ↳ **`TableCellProps`**

  ↳↳ [`DataTableCellProps`](DataTableCellProps.md)

## Table of contents

### Properties

- [children](TableCellProps.md#children)
- [fontSize](TableCellProps.md#fontsize)
- [includeBottomBorder](TableCellProps.md#includebottomborder)
- [includeLeftBorder](TableCellProps.md#includeleftborder)
- [includeRightBorder](TableCellProps.md#includerightborder)
- [includeTopBorder](TableCellProps.md#includetopborder)
- [isHeader](TableCellProps.md#isheader)
- [style](TableCellProps.md#style)
- [textAlign](TableCellProps.md#textalign)
- [weighting](TableCellProps.md#weighting)

## Properties

### children

• `Optional` **children**: `ReactNode`

#### Inherited from

React.PropsWithChildren.children

#### Defined in

node_modules/.pnpm/@types+react@18.0.37/node_modules/@types/react/ts5.0/index.d.ts:778

___

### fontSize

• `Optional` **fontSize**: `string` \| `number`

The font-size to apply to the cell.

#### Defined in

[src/TableCell.tsx:56](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L56)

___

### includeBottomBorder

• `Optional` **includeBottomBorder**: `boolean`

Include the bottom border. Default true.

#### Inherited from

[TableBorder](TableBorder.md).[includeBottomBorder](TableBorder.md#includebottomborder)

#### Defined in

[src/TableCell.tsx:23](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L23)

___

### includeLeftBorder

• `Optional` **includeLeftBorder**: `boolean`

Include the left border. Default true.

#### Inherited from

[TableBorder](TableBorder.md).[includeLeftBorder](TableBorder.md#includeleftborder)

#### Defined in

[src/TableCell.tsx:28](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L28)

___

### includeRightBorder

• `Optional` **includeRightBorder**: `boolean`

Include the right border. Default true.

#### Inherited from

[TableBorder](TableBorder.md).[includeRightBorder](TableBorder.md#includerightborder)

#### Defined in

[src/TableCell.tsx:18](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L18)

___

### includeTopBorder

• `Optional` **includeTopBorder**: `boolean`

Include the top border. Default true.

#### Inherited from

[TableBorder](TableBorder.md).[includeTopBorder](TableBorder.md#includetopborder)

#### Defined in

[src/TableCell.tsx:13](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L13)

___

### isHeader

• `Optional` **isHeader**: `boolean`

Whether this is a header cell or not. If not defined it will be false.

#### Defined in

[src/TableCell.tsx:51](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L51)

___

### style

• `Optional` **style**: `Style` \| `Style`[]

Extra styling to apply. These will override existing style with the same key.

#### Defined in

[src/TableCell.tsx:41](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L41)

___

### textAlign

• `Optional` **textAlign**: ``"center"`` \| ``"left"`` \| ``"right"``

How to align the text

#### Defined in

[src/TableCell.tsx:46](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L46)

___

### weighting

• `Optional` **weighting**: `number`

The weighting of a cell based on the flex layout style.
This value is between 0..1, if not specified 1 is assumed, this will take up the remaining available space.

#### Defined in

[src/TableCell.tsx:36](https://github.com/propra-tech/react-pdf-table/blob/65981e2/src/TableCell.tsx#L36)
