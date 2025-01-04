# Use Hooks

## `Dùng khi nào?`
Khi muốn dữ liệu thay đổi thì giao diện tự động được 
cập nhật (re-render lại theo dữ liệu) .

### Cách dùng

```
import { useState } from 'react'

function Component(){
    const [state, setState] = useState()
    ...
}
```
### Lưu ý:
- Component được re-render sau khi `setState`
- Initial state chỉ được dùng cho lần đầu
- Set state với callback?
- Initial state với callback?
- Set state là thay thế state bằng một giá trị mới (giá trị sẽ được cập nhật cho lần render tới)