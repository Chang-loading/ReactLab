Typescript 是JavaScript的superset；

> Boolean 类型
```javascript
let isDone: boolean = false;
// ES5：var isDone = false;
```
> Number 类型
```javascript
let count: number = 10;
// ES5：var count = 10;
```
> String 类型
```javascript
let name: string = "Semliker";
// ES5：var name = 'Semlinker';
```
> Array 类型
```javascript
let list: number[] = [1, 2, 3];
// ES5：var list = [1,2,3];

let list: Array<number> = [1, 2, 3]; // Array<number>泛型语法
// ES5：var list = [1,2,3];
```
> Enum 类型
```javascript
enum Direction {
  NORTH,
  SOUTH,
  EAST,
  WEST,
}

let dir: Direction = Direction.NORTH;
```
> Any 类型 > 顶级类型: 
any 类型本质上是类型系统的一个逃逸舱
```javascript
let notSure: any = 666;
notSure = "Semlinker";
notSure = false;

```
> Unkown 类型 > 顶级类型:
unknown 类型只能被赋值给any类型和unknown类型本身
``` javascript
let value: unknown;

value = true; // OK
value = 42; // OK
value = "Hello World"; // OK
value = []; // OK
value = {}; // OK
value = Math.random; // OK
value = null; // OK
value = undefined; // OK
value = new TypeError(); // OK
value = Symbol("type"); // OK
```
> Tuple 类型
``` javascript
let tupleType: [string, boolean];
tupleType = ["Semlinker", true];
```

》 产品经理：
发现需求，建立用户画像， 竞品分析Conpetitive Product Analysis，

prototyping：axure
产品需求文档：Product Requirement Document；
需求评审
项目管理
项目测试验收上线
版本迭代


了解产品上线流程
需求调研
竞品分析C
