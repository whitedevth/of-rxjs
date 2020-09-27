### ตัวอย่างการใช้งาน of ใน rxjs [Learn RxJS](https://www.learnrxjs.io/learn-rxjs/operators/creation/of)
 
 #### สร้าง observable ตามลำดับค่าที่ได้แล้ว completed

```
import { of } from 'rxjs';

// สร้าง observable
const source = of(1, 2, 3, [4, 5]);

// ผลลัพธ์
// 1
// 2
// 3
// [ 4, 5 ]
source.subscribe(console.log);
```
