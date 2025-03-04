---
id: "qtablewidget"
title: "QTableWidget"
sidebar_label: "QTableWidget"
---

> Creates and item-based table view.

**This class is a JS wrapper around Qt's [QTableWidget class](https://doc.qt.io/qt-5/qtablewidget.html)**

### Example

```javascript
const { QTableWidget, QMainWindow, QTableWidgetItem } = require("@nodegui/nodegui");

const win = new QMainWindow();
const table = new QTableWidget(2, 3);
table.setHorizontalHeaderLabels(['first', 'second', 'third']);

const cell00 = new QTableWidgetItem('C00');
const cell01 = new QTableWidgetItem('C01');
const cell10 = new QTableWidgetItem('C10');
const cell11 = new QTableWidgetItem('C11');

table.setItem(0, 0, cell00);
table.setItem(0, 1, cell01);
table.setItem(1, 0, cell10);
table.setItem(1, 1, cell11);

win.setCentralWidget(table);
win.show();
(global as any).win = win;

```

## Hierarchy

  ↳ [QAbstractScrollArea](qabstractscrollarea.md)‹[QTableWidgetSignals](../interfaces/qtablewidgetsignals.md)›

  ↳ **QTableWidget**

## Index

### Constructors

* [constructor](qtablewidget.md#constructor)

### Properties

* [_rawInlineStyle](qtablewidget.md#_rawinlinestyle)
* [actions](qtablewidget.md#actions)
* [items](qtablewidget.md#items)
* [layout](qtablewidget.md#optional-layout)
* [native](qtablewidget.md#native)
* [nodeChildren](qtablewidget.md#nodechildren)
* [nodeParent](qtablewidget.md#optional-nodeparent)
* [type](qtablewidget.md#type)
* [viewportWidget](qtablewidget.md#optional-viewportwidget)

### Methods

* [activateWindow](qtablewidget.md#activatewindow)
* [addAction](qtablewidget.md#addaction)
* [addEventListener](qtablewidget.md#addeventlistener)
* [adjustSize](qtablewidget.md#adjustsize)
* [clear](qtablewidget.md#clear)
* [clearContents](qtablewidget.md#clearcontents)
* [close](qtablewidget.md#close)
* [closePersistentEditor](qtablewidget.md#closepersistenteditor)
* [editItem](qtablewidget.md#edititem)
* [font](qtablewidget.md#font)
* [geometry](qtablewidget.md#geometry)
* [getFlexNode](qtablewidget.md#getflexnode)
* [hasMouseTracking](qtablewidget.md#hasmousetracking)
* [hide](qtablewidget.md#hide)
* [hideColumn](qtablewidget.md#hidecolumn)
* [hideRow](qtablewidget.md#hiderow)
* [inherits](qtablewidget.md#inherits)
* [insertColumn](qtablewidget.md#insertcolumn)
* [insertRow](qtablewidget.md#insertrow)
* [isEnabled](qtablewidget.md#isenabled)
* [isSortingEnabled](qtablewidget.md#issortingenabled)
* [isVisible](qtablewidget.md#isvisible)
* [lower](qtablewidget.md#lower)
* [move](qtablewidget.md#move)
* [objectName](qtablewidget.md#objectname)
* [pos](qtablewidget.md#pos)
* [property](qtablewidget.md#property)
* [raise](qtablewidget.md#raise)
* [removeColumn](qtablewidget.md#removecolumn)
* [removeEventListener](qtablewidget.md#removeeventlistener)
* [removeRow](qtablewidget.md#removerow)
* [repaint](qtablewidget.md#repaint)
* [resize](qtablewidget.md#resize)
* [resizeColumnToContents](qtablewidget.md#resizecolumntocontents)
* [resizeColumnsToContents](qtablewidget.md#resizecolumnstocontents)
* [resizeRowToContents](qtablewidget.md#resizerowtocontents)
* [resizeRowsToContents](qtablewidget.md#resizerowstocontents)
* [scrollToItem](qtablewidget.md#scrolltoitem)
* [selectColumn](qtablewidget.md#selectcolumn)
* [selectRow](qtablewidget.md#selectrow)
* [selectedRanges](qtablewidget.md#selectedranges)
* [setAttribute](qtablewidget.md#setattribute)
* [setCellWidget](qtablewidget.md#setcellwidget)
* [setColumnWidth](qtablewidget.md#setcolumnwidth)
* [setContextMenuPolicy](qtablewidget.md#setcontextmenupolicy)
* [setCursor](qtablewidget.md#setcursor)
* [setEnabled](qtablewidget.md#setenabled)
* [setFixedSize](qtablewidget.md#setfixedsize)
* [setFlexNodeSizeControlled](qtablewidget.md#setflexnodesizecontrolled)
* [setFont](qtablewidget.md#setfont)
* [setGeometry](qtablewidget.md#setgeometry)
* [setHorizontalHeaderItem](qtablewidget.md#sethorizontalheaderitem)
* [setHorizontalHeaderLabels](qtablewidget.md#sethorizontalheaderlabels)
* [setHorizontalScrollBarPolicy](qtablewidget.md#sethorizontalscrollbarpolicy)
* [setInlineStyle](qtablewidget.md#setinlinestyle)
* [setItem](qtablewidget.md#setitem)
* [setLayout](qtablewidget.md#setlayout)
* [setMaximumSize](qtablewidget.md#setmaximumsize)
* [setMinimumSize](qtablewidget.md#setminimumsize)
* [setMouseTracking](qtablewidget.md#setmousetracking)
* [setNodeParent](qtablewidget.md#setnodeparent)
* [setObjectName](qtablewidget.md#setobjectname)
* [setProperty](qtablewidget.md#setproperty)
* [setRowHeight](qtablewidget.md#setrowheight)
* [setShowGrid](qtablewidget.md#setshowgrid)
* [setSortingEnabled](qtablewidget.md#setsortingenabled)
* [setStyleSheet](qtablewidget.md#setstylesheet)
* [setVerticalHeaderItem](qtablewidget.md#setverticalheaderitem)
* [setVerticalHeaderLabels](qtablewidget.md#setverticalheaderlabels)
* [setVerticalScrollBarPolicy](qtablewidget.md#setverticalscrollbarpolicy)
* [setViewport](qtablewidget.md#setviewport)
* [setWindowFlag](qtablewidget.md#setwindowflag)
* [setWindowIcon](qtablewidget.md#setwindowicon)
* [setWindowOpacity](qtablewidget.md#setwindowopacity)
* [setWindowState](qtablewidget.md#setwindowstate)
* [setWindowTitle](qtablewidget.md#setwindowtitle)
* [show](qtablewidget.md#show)
* [showColumn](qtablewidget.md#showcolumn)
* [showFullScreen](qtablewidget.md#showfullscreen)
* [showGrid](qtablewidget.md#showgrid)
* [showMaximized](qtablewidget.md#showmaximized)
* [showMinimized](qtablewidget.md#showminimized)
* [showNormal](qtablewidget.md#shownormal)
* [showRow](qtablewidget.md#showrow)
* [size](qtablewidget.md#size)
* [sortByColumn](qtablewidget.md#sortbycolumn)
* [styleSheet](qtablewidget.md#stylesheet)
* [testAttribute](qtablewidget.md#testattribute)
* [update](qtablewidget.md#update)
* [updateGeometry](qtablewidget.md#updategeometry)
* [viewport](qtablewidget.md#viewport)
* [windowOpacity](qtablewidget.md#windowopacity)
* [windowState](qtablewidget.md#windowstate)
* [windowTitle](qtablewidget.md#windowtitle)

## Constructors

###  constructor

\+ **new QTableWidget**(`rows`: number, `columns`: number): *[QTableWidget](qtablewidget.md)*

*Overrides [EventWidget](eventwidget.md).[constructor](eventwidget.md#constructor)*

**Parameters:**

Name | Type |
------ | ------ |
`rows` | number |
`columns` | number |

**Returns:** *[QTableWidget](qtablewidget.md)*

\+ **new QTableWidget**(`rows`: number, `columns`: number, `parent`: [NodeWidget](nodewidget.md)‹any›): *[QTableWidget](qtablewidget.md)*

*Overrides [EventWidget](eventwidget.md).[constructor](eventwidget.md#constructor)*

**Parameters:**

Name | Type |
------ | ------ |
`rows` | number |
`columns` | number |
`parent` | [NodeWidget](nodewidget.md)‹any› |

**Returns:** *[QTableWidget](qtablewidget.md)*

## Properties

###  _rawInlineStyle

• **_rawInlineStyle**: *string* = ""

*Inherited from [QMenu](qmenu.md).[_rawInlineStyle](qmenu.md#_rawinlinestyle)*

___

###  actions

• **actions**: *Set‹[QAction](qaction.md)‹››* = new Set<QAction>()

*Inherited from [QMenu](qmenu.md).[actions](qmenu.md#actions)*

___

###  items

• **items**: *Set‹[NativeElement](../globals.md#nativeelement) | [Component](component.md)›*

___

### `Optional` layout

• **layout**? : *[NodeLayout](nodelayout.md)‹[QTableWidgetSignals](../interfaces/qtablewidgetsignals.md)›*

*Inherited from [QMenu](qmenu.md).[layout](qmenu.md#optional-layout)*

___

###  native

• **native**: *[NativeElement](../globals.md#nativeelement)*

*Overrides [Component](component.md).[native](component.md#abstract-native)*

___

###  nodeChildren

• **nodeChildren**: *Set‹[Component](component.md)›*

*Inherited from [Component](component.md).[nodeChildren](component.md#nodechildren)*

___

### `Optional` nodeParent

• **nodeParent**? : *[Component](component.md)*

*Inherited from [Component](component.md).[nodeParent](component.md#optional-nodeparent)*

___

###  type

• **type**: *string* = "widget"

*Inherited from [QMenu](qmenu.md).[type](qmenu.md#type)*

___

### `Optional` viewportWidget

• **viewportWidget**? : *[NodeWidget](nodewidget.md)‹any›*

*Inherited from [QAbstractScrollArea](qabstractscrollarea.md).[viewportWidget](qabstractscrollarea.md#optional-viewportwidget)*

## Methods

###  activateWindow

▸ **activateWindow**(): *void*

*Inherited from [QMenu](qmenu.md).[activateWindow](qmenu.md#activatewindow)*

**Returns:** *void*

___

###  addAction

▸ **addAction**(`action`: [QAction](qaction.md) | string): *[QAction](qaction.md)*

*Inherited from [QMenu](qmenu.md).[addAction](qmenu.md#addaction)*

**Parameters:**

Name | Type |
------ | ------ |
`action` | [QAction](qaction.md) &#124; string |

**Returns:** *[QAction](qaction.md)*

___

###  addEventListener

▸ **addEventListener**<**SignalType**>(`signalType`: SignalType, `callback`: QTableWidgetSignals[SignalType]): *void*

*Inherited from [EventWidget](eventwidget.md).[addEventListener](eventwidget.md#addeventlistener)*

**Type parameters:**

▪ **SignalType**: *keyof QTableWidgetSignals*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`signalType` | SignalType | SignalType is a signal from the widgets signals interface. |
`callback` | QTableWidgetSignals[SignalType] | Corresponding callback for the signal as mentioned in the widget's signal interface |

**Returns:** *void*

void

For example in the case of QPushButton:
```js
const button = new QPushButton();
button.addEventListener('clicked',(checked)=>console.log("clicked"));
// here clicked is a value from QPushButtonSignals interface
```

▸ **addEventListener**(`eventType`: [WidgetEventTypes](../enums/widgeteventtypes.md), `callback`: function): *void*

*Inherited from [EventWidget](eventwidget.md).[addEventListener](eventwidget.md#addeventlistener)*

**Parameters:**

▪ **eventType**: *[WidgetEventTypes](../enums/widgeteventtypes.md)*

▪ **callback**: *function*

For example in the case of QPushButton:
```js
const button = new QPushButton();
button.addEventListener(WidgetEventTypes.HoverEnter,()=>console.log("hovered"));
```

▸ (`event?`: [NativeRawPointer](../globals.md#nativerawpointer)‹"QEvent"›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`event?` | [NativeRawPointer](../globals.md#nativerawpointer)‹"QEvent"› |

**Returns:** *void*

___

###  adjustSize

▸ **adjustSize**(): *void*

*Inherited from [QMenu](qmenu.md).[adjustSize](qmenu.md#adjustsize)*

**Returns:** *void*

___

###  clear

▸ **clear**(): *void*

**Returns:** *void*

___

###  clearContents

▸ **clearContents**(): *void*

**Returns:** *void*

___

###  close

▸ **close**(): *boolean*

*Inherited from [QMenu](qmenu.md).[close](qmenu.md#close)*

**Returns:** *boolean*

___

###  closePersistentEditor

▸ **closePersistentEditor**(`item`: [QTableWidgetItem](qtablewidgetitem.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`item` | [QTableWidgetItem](qtablewidgetitem.md) |

**Returns:** *void*

___

###  editItem

▸ **editItem**(`item`: [Component](component.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`item` | [Component](component.md) |

**Returns:** *void*

___

###  font

▸ **font**(): *[QFont](qfont.md)*

*Inherited from [QMenu](qmenu.md).[font](qmenu.md#font)*

**Returns:** *[QFont](qfont.md)*

___

###  geometry

▸ **geometry**(): *[QRect](qrect.md)*

*Inherited from [QMenu](qmenu.md).[geometry](qmenu.md#geometry)*

**Returns:** *[QRect](qrect.md)*

___

###  getFlexNode

▸ **getFlexNode**(): *[FlexNode](../globals.md#flexnode)*

*Inherited from [YogaWidget](yogawidget.md).[getFlexNode](yogawidget.md#getflexnode)*

**Returns:** *[FlexNode](../globals.md#flexnode)*

___

###  hasMouseTracking

▸ **hasMouseTracking**(): *boolean*

*Inherited from [QMenu](qmenu.md).[hasMouseTracking](qmenu.md#hasmousetracking)*

**Returns:** *boolean*

___

###  hide

▸ **hide**(): *void*

*Inherited from [QMenu](qmenu.md).[hide](qmenu.md#hide)*

**Returns:** *void*

___

###  hideColumn

▸ **hideColumn**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  hideRow

▸ **hideRow**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  inherits

▸ **inherits**(`className`: string): *boolean*

*Inherited from [NodeObject](nodeobject.md).[inherits](nodeobject.md#inherits)*

**Parameters:**

Name | Type |
------ | ------ |
`className` | string |

**Returns:** *boolean*

___

###  insertColumn

▸ **insertColumn**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  insertRow

▸ **insertRow**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  isEnabled

▸ **isEnabled**(): *boolean*

*Inherited from [QMenu](qmenu.md).[isEnabled](qmenu.md#isenabled)*

**Returns:** *boolean*

___

###  isSortingEnabled

▸ **isSortingEnabled**(): *boolean*

**Returns:** *boolean*

___

###  isVisible

▸ **isVisible**(): *boolean*

*Inherited from [QMenu](qmenu.md).[isVisible](qmenu.md#isvisible)*

**Returns:** *boolean*

___

###  lower

▸ **lower**(): *void*

*Inherited from [QMenu](qmenu.md).[lower](qmenu.md#lower)*

**Returns:** *void*

___

###  move

▸ **move**(`x`: number, `y`: number): *void*

*Inherited from [QMenu](qmenu.md).[move](qmenu.md#move)*

**Parameters:**

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

**Returns:** *void*

___

###  objectName

▸ **objectName**(): *string*

*Inherited from [NodeObject](nodeobject.md).[objectName](nodeobject.md#objectname)*

**Returns:** *string*

___

###  pos

▸ **pos**(): *object*

*Inherited from [QMenu](qmenu.md).[pos](qmenu.md#pos)*

**Returns:** *object*

* **x**: *number*

* **y**: *number*

___

###  property

▸ **property**(`name`: string): *[QVariant](qvariant.md)*

*Inherited from [NodeObject](nodeobject.md).[property](nodeobject.md#property)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *[QVariant](qvariant.md)*

___

###  raise

▸ **raise**(): *void*

*Inherited from [QMenu](qmenu.md).[raise](qmenu.md#raise)*

**Returns:** *void*

___

###  removeColumn

▸ **removeColumn**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  removeEventListener

▸ **removeEventListener**<**SignalType**>(`signalType`: SignalType, `callback`: QTableWidgetSignals[SignalType]): *void*

*Inherited from [EventWidget](eventwidget.md).[removeEventListener](eventwidget.md#removeeventlistener)*

**Type parameters:**

▪ **SignalType**: *keyof QTableWidgetSignals*

**Parameters:**

Name | Type |
------ | ------ |
`signalType` | SignalType |
`callback` | QTableWidgetSignals[SignalType] |

**Returns:** *void*

▸ **removeEventListener**(`eventType`: [WidgetEventTypes](../enums/widgeteventtypes.md), `callback`: function): *void*

*Inherited from [EventWidget](eventwidget.md).[removeEventListener](eventwidget.md#removeeventlistener)*

**Parameters:**

▪ **eventType**: *[WidgetEventTypes](../enums/widgeteventtypes.md)*

▪ **callback**: *function*

▸ (`event?`: [NativeRawPointer](../globals.md#nativerawpointer)‹"QEvent"›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`event?` | [NativeRawPointer](../globals.md#nativerawpointer)‹"QEvent"› |

**Returns:** *void*

___

###  removeRow

▸ **removeRow**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  repaint

▸ **repaint**(): *void*

*Inherited from [QMenu](qmenu.md).[repaint](qmenu.md#repaint)*

**Returns:** *void*

___

###  resize

▸ **resize**(`width`: number, `height`: number): *void*

*Inherited from [QMenu](qmenu.md).[resize](qmenu.md#resize)*

**Parameters:**

Name | Type |
------ | ------ |
`width` | number |
`height` | number |

**Returns:** *void*

___

###  resizeColumnToContents

▸ **resizeColumnToContents**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  resizeColumnsToContents

▸ **resizeColumnsToContents**(): *void*

**Returns:** *void*

___

###  resizeRowToContents

▸ **resizeRowToContents**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  resizeRowsToContents

▸ **resizeRowsToContents**(): *void*

**Returns:** *void*

___

###  scrollToItem

▸ **scrollToItem**(`item`: [QTableWidgetItem](qtablewidgetitem.md), `hint`: [ScrollHint](../enums/scrollhint.md)): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`item` | [QTableWidgetItem](qtablewidgetitem.md) | - |
`hint` | [ScrollHint](../enums/scrollhint.md) | ScrollHint.EnsureVisible |

**Returns:** *void*

___

###  selectColumn

▸ **selectColumn**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  selectRow

▸ **selectRow**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  selectedRanges

▸ **selectedRanges**(): *[Range](../interfaces/range.md)[]*

**Returns:** *[Range](../interfaces/range.md)[]*

___

###  setAttribute

▸ **setAttribute**(`attribute`: [WidgetAttribute](../enums/widgetattribute.md), `switchOn`: boolean): *void*

*Inherited from [QMenu](qmenu.md).[setAttribute](qmenu.md#setattribute)*

**Parameters:**

Name | Type |
------ | ------ |
`attribute` | [WidgetAttribute](../enums/widgetattribute.md) |
`switchOn` | boolean |

**Returns:** *void*

___

###  setCellWidget

▸ **setCellWidget**(`row`: number, `column`: number, `widget`: [NodeWidget](nodewidget.md)‹any›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |
`column` | number |
`widget` | [NodeWidget](nodewidget.md)‹any› |

**Returns:** *void*

___

###  setColumnWidth

▸ **setColumnWidth**(`column`: number, `width`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |
`width` | number |

**Returns:** *void*

___

###  setContextMenuPolicy

▸ **setContextMenuPolicy**(`contextMenuPolicy`: [ContextMenuPolicy](../enums/contextmenupolicy.md)): *void*

*Inherited from [QMenu](qmenu.md).[setContextMenuPolicy](qmenu.md#setcontextmenupolicy)*

**Parameters:**

Name | Type |
------ | ------ |
`contextMenuPolicy` | [ContextMenuPolicy](../enums/contextmenupolicy.md) |

**Returns:** *void*

___

###  setCursor

▸ **setCursor**(`cursor`: [CursorShape](../enums/cursorshape.md) | [QCursor](qcursor.md)): *void*

*Inherited from [QMenu](qmenu.md).[setCursor](qmenu.md#setcursor)*

**Parameters:**

Name | Type |
------ | ------ |
`cursor` | [CursorShape](../enums/cursorshape.md) &#124; [QCursor](qcursor.md) |

**Returns:** *void*

___

###  setEnabled

▸ **setEnabled**(`enabled`: boolean): *void*

*Inherited from [QMenu](qmenu.md).[setEnabled](qmenu.md#setenabled)*

**Parameters:**

Name | Type |
------ | ------ |
`enabled` | boolean |

**Returns:** *void*

___

###  setFixedSize

▸ **setFixedSize**(`width`: number, `height`: number): *void*

*Inherited from [QMenu](qmenu.md).[setFixedSize](qmenu.md#setfixedsize)*

**Parameters:**

Name | Type |
------ | ------ |
`width` | number |
`height` | number |

**Returns:** *void*

___

###  setFlexNodeSizeControlled

▸ **setFlexNodeSizeControlled**(`isSizeControlled`: boolean): *void*

*Inherited from [YogaWidget](yogawidget.md).[setFlexNodeSizeControlled](yogawidget.md#setflexnodesizecontrolled)*

sets whether the widget's size is controlled by someone else (for example a window's size is controlled by its frame when dragged).

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isSizeControlled` | boolean |   |

**Returns:** *void*

___

###  setFont

▸ **setFont**(`font`: [QFont](qfont.md)): *void*

*Inherited from [QMenu](qmenu.md).[setFont](qmenu.md#setfont)*

**Parameters:**

Name | Type |
------ | ------ |
`font` | [QFont](qfont.md) |

**Returns:** *void*

___

###  setGeometry

▸ **setGeometry**(`x`: number, `y`: number, `w`: number, `h`: number): *void*

*Inherited from [QMenu](qmenu.md).[setGeometry](qmenu.md#setgeometry)*

**Parameters:**

Name | Type |
------ | ------ |
`x` | number |
`y` | number |
`w` | number |
`h` | number |

**Returns:** *void*

___

###  setHorizontalHeaderItem

▸ **setHorizontalHeaderItem**(`column`: number, `item`: [QTableWidgetItem](qtablewidgetitem.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |
`item` | [QTableWidgetItem](qtablewidgetitem.md) |

**Returns:** *void*

___

###  setHorizontalHeaderLabels

▸ **setHorizontalHeaderLabels**(`labels`: string[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`labels` | string[] |

**Returns:** *void*

___

###  setHorizontalScrollBarPolicy

▸ **setHorizontalScrollBarPolicy**(`policy`: [ScrollBarPolicy](../enums/scrollbarpolicy.md)): *void*

*Inherited from [QAbstractScrollArea](qabstractscrollarea.md).[setHorizontalScrollBarPolicy](qabstractscrollarea.md#sethorizontalscrollbarpolicy)*

**Parameters:**

Name | Type |
------ | ------ |
`policy` | [ScrollBarPolicy](../enums/scrollbarpolicy.md) |

**Returns:** *void*

___

###  setInlineStyle

▸ **setInlineStyle**(`style`: string): *void*

*Inherited from [QMenu](qmenu.md).[setInlineStyle](qmenu.md#setinlinestyle)*

**Parameters:**

Name | Type |
------ | ------ |
`style` | string |

**Returns:** *void*

___

###  setItem

▸ **setItem**(`row`: number, `column`: number, `item`: [QTableWidgetItem](qtablewidgetitem.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |
`column` | number |
`item` | [QTableWidgetItem](qtablewidgetitem.md) |

**Returns:** *void*

___

###  setLayout

▸ **setLayout**(`parentLayout`: [NodeLayout](nodelayout.md)‹[QTableWidgetSignals](../interfaces/qtablewidgetsignals.md)›): *void*

*Inherited from [QMenu](qmenu.md).[setLayout](qmenu.md#setlayout)*

**Parameters:**

Name | Type |
------ | ------ |
`parentLayout` | [NodeLayout](nodelayout.md)‹[QTableWidgetSignals](../interfaces/qtablewidgetsignals.md)› |

**Returns:** *void*

___

###  setMaximumSize

▸ **setMaximumSize**(`maxw`: number, `maxh`: number): *void*

*Inherited from [QMenu](qmenu.md).[setMaximumSize](qmenu.md#setmaximumsize)*

**Parameters:**

Name | Type |
------ | ------ |
`maxw` | number |
`maxh` | number |

**Returns:** *void*

___

###  setMinimumSize

▸ **setMinimumSize**(`minw`: number, `minh`: number): *void*

*Inherited from [QMenu](qmenu.md).[setMinimumSize](qmenu.md#setminimumsize)*

**Parameters:**

Name | Type |
------ | ------ |
`minw` | number |
`minh` | number |

**Returns:** *void*

___

###  setMouseTracking

▸ **setMouseTracking**(`isMouseTracked`: boolean): *void*

*Inherited from [QMenu](qmenu.md).[setMouseTracking](qmenu.md#setmousetracking)*

**Parameters:**

Name | Type |
------ | ------ |
`isMouseTracked` | boolean |

**Returns:** *void*

___

###  setNodeParent

▸ **setNodeParent**(`parent?`: [Component](component.md)): *void*

*Inherited from [Component](component.md).[setNodeParent](component.md#setnodeparent)*

**Parameters:**

Name | Type |
------ | ------ |
`parent?` | [Component](component.md) |

**Returns:** *void*

___

###  setObjectName

▸ **setObjectName**(`objectName`: string): *void*

*Inherited from [QMenu](qmenu.md).[setObjectName](qmenu.md#setobjectname)*

*Overrides [NodeObject](nodeobject.md).[setObjectName](nodeobject.md#setobjectname)*

**Parameters:**

Name | Type |
------ | ------ |
`objectName` | string |

**Returns:** *void*

___

###  setProperty

▸ **setProperty**(`name`: string, `value`: [QVariantType](../globals.md#qvarianttype)): *boolean*

*Inherited from [NodeObject](nodeobject.md).[setProperty](nodeobject.md#setproperty)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`value` | [QVariantType](../globals.md#qvarianttype) |

**Returns:** *boolean*

___

###  setRowHeight

▸ **setRowHeight**(`row`: number, `height`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |
`height` | number |

**Returns:** *void*

___

###  setShowGrid

▸ **setShowGrid**(`show`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`show` | boolean |

**Returns:** *void*

___

###  setSortingEnabled

▸ **setSortingEnabled**(`enable`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`enable` | boolean |

**Returns:** *void*

___

###  setStyleSheet

▸ **setStyleSheet**(`styleSheet`: string): *void*

*Inherited from [QMenu](qmenu.md).[setStyleSheet](qmenu.md#setstylesheet)*

**Parameters:**

Name | Type |
------ | ------ |
`styleSheet` | string |

**Returns:** *void*

___

###  setVerticalHeaderItem

▸ **setVerticalHeaderItem**(`row`: number, `item`: [QTableWidgetItem](qtablewidgetitem.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |
`item` | [QTableWidgetItem](qtablewidgetitem.md) |

**Returns:** *void*

___

###  setVerticalHeaderLabels

▸ **setVerticalHeaderLabels**(`labels`: string[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`labels` | string[] |

**Returns:** *void*

___

###  setVerticalScrollBarPolicy

▸ **setVerticalScrollBarPolicy**(`policy`: [ScrollBarPolicy](../enums/scrollbarpolicy.md)): *void*

*Inherited from [QAbstractScrollArea](qabstractscrollarea.md).[setVerticalScrollBarPolicy](qabstractscrollarea.md#setverticalscrollbarpolicy)*

**Parameters:**

Name | Type |
------ | ------ |
`policy` | [ScrollBarPolicy](../enums/scrollbarpolicy.md) |

**Returns:** *void*

___

###  setViewport

▸ **setViewport**(`widget`: [NodeWidget](nodewidget.md)‹any›): *void*

*Inherited from [QAbstractScrollArea](qabstractscrollarea.md).[setViewport](qabstractscrollarea.md#setviewport)*

**Parameters:**

Name | Type |
------ | ------ |
`widget` | [NodeWidget](nodewidget.md)‹any› |

**Returns:** *void*

___

###  setWindowFlag

▸ **setWindowFlag**(`windowType`: [WindowType](../enums/windowtype.md), `switchOn`: boolean): *void*

*Inherited from [QMenu](qmenu.md).[setWindowFlag](qmenu.md#setwindowflag)*

**Parameters:**

Name | Type |
------ | ------ |
`windowType` | [WindowType](../enums/windowtype.md) |
`switchOn` | boolean |

**Returns:** *void*

___

###  setWindowIcon

▸ **setWindowIcon**(`icon`: [QIcon](qicon.md)): *void*

*Inherited from [QMenu](qmenu.md).[setWindowIcon](qmenu.md#setwindowicon)*

**Parameters:**

Name | Type |
------ | ------ |
`icon` | [QIcon](qicon.md) |

**Returns:** *void*

___

###  setWindowOpacity

▸ **setWindowOpacity**(`opacity`: number): *void*

*Inherited from [QMenu](qmenu.md).[setWindowOpacity](qmenu.md#setwindowopacity)*

**Parameters:**

Name | Type |
------ | ------ |
`opacity` | number |

**Returns:** *void*

___

###  setWindowState

▸ **setWindowState**(`state`: [WindowState](../enums/windowstate.md)): *void*

*Inherited from [QMenu](qmenu.md).[setWindowState](qmenu.md#setwindowstate)*

**Parameters:**

Name | Type |
------ | ------ |
`state` | [WindowState](../enums/windowstate.md) |

**Returns:** *void*

___

###  setWindowTitle

▸ **setWindowTitle**(`title`: string): *void*

*Inherited from [QMenu](qmenu.md).[setWindowTitle](qmenu.md#setwindowtitle)*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |

**Returns:** *void*

___

###  show

▸ **show**(): *void*

*Inherited from [QMenu](qmenu.md).[show](qmenu.md#show)*

**Returns:** *void*

___

###  showColumn

▸ **showColumn**(`column`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |

**Returns:** *void*

___

###  showFullScreen

▸ **showFullScreen**(): *void*

*Inherited from [QMenu](qmenu.md).[showFullScreen](qmenu.md#showfullscreen)*

**Returns:** *void*

___

###  showGrid

▸ **showGrid**(): *boolean*

**Returns:** *boolean*

___

###  showMaximized

▸ **showMaximized**(): *void*

*Inherited from [QMenu](qmenu.md).[showMaximized](qmenu.md#showmaximized)*

**Returns:** *void*

___

###  showMinimized

▸ **showMinimized**(): *void*

*Inherited from [QMenu](qmenu.md).[showMinimized](qmenu.md#showminimized)*

**Returns:** *void*

___

###  showNormal

▸ **showNormal**(): *void*

*Inherited from [QMenu](qmenu.md).[showNormal](qmenu.md#shownormal)*

**Returns:** *void*

___

###  showRow

▸ **showRow**(`row`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`row` | number |

**Returns:** *void*

___

###  size

▸ **size**(): *[QSize](qsize.md)*

*Inherited from [QMenu](qmenu.md).[size](qmenu.md#size)*

**Returns:** *[QSize](qsize.md)*

___

###  sortByColumn

▸ **sortByColumn**(`column`: number, `order`: [SortOrder](../enums/sortorder.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`column` | number |
`order` | [SortOrder](../enums/sortorder.md) |

**Returns:** *void*

___

###  styleSheet

▸ **styleSheet**(): *string*

*Inherited from [QMenu](qmenu.md).[styleSheet](qmenu.md#stylesheet)*

**Returns:** *string*

___

###  testAttribute

▸ **testAttribute**(`attribute`: [WidgetAttribute](../enums/widgetattribute.md)): *boolean*

*Inherited from [QMenu](qmenu.md).[testAttribute](qmenu.md#testattribute)*

**Parameters:**

Name | Type |
------ | ------ |
`attribute` | [WidgetAttribute](../enums/widgetattribute.md) |

**Returns:** *boolean*

___

###  update

▸ **update**(): *void*

*Inherited from [QMenu](qmenu.md).[update](qmenu.md#update)*

**Returns:** *void*

___

###  updateGeometry

▸ **updateGeometry**(): *void*

*Inherited from [QMenu](qmenu.md).[updateGeometry](qmenu.md#updategeometry)*

**Returns:** *void*

___

###  viewport

▸ **viewport**(): *[QWidget](qwidget.md)*

*Inherited from [QAbstractScrollArea](qabstractscrollarea.md).[viewport](qabstractscrollarea.md#viewport)*

**Returns:** *[QWidget](qwidget.md)*

___

###  windowOpacity

▸ **windowOpacity**(): *number*

*Inherited from [QMenu](qmenu.md).[windowOpacity](qmenu.md#windowopacity)*

**Returns:** *number*

___

###  windowState

▸ **windowState**(): *number*

*Inherited from [QMenu](qmenu.md).[windowState](qmenu.md#windowstate)*

**Returns:** *number*

___

###  windowTitle

▸ **windowTitle**(): *string*

*Inherited from [QMenu](qmenu.md).[windowTitle](qmenu.md#windowtitle)*

**Returns:** *string*
