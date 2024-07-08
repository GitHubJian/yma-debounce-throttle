# YMA Debounce & Throttle

防抖（debounce）和节流（throttle）

## Usage

### Debounce

-   n 秒后在执行该事件，若在 n 秒内被重复触发，则重新计时
-   强制函数在某段时间内执行一次

##### immediate

-   type: `boolean`
-   default: `false`

为 `true` 表示在一个时间区间的最开始执行

### Throttle

-   n 秒内只运行一次，若在 n 秒内重复触发，只有一次生效
-   强制函数以固定的速率执行

#### options

##### leading

禁用第一次执行

-   type: `boolean`
-   default: `false`

##### trailing

禁用最后一次执行

-   type: `boolean`
-   default: `false`
