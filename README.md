# Todolist RESTful API kata

1.server.js
<br>
⭐ 需要先宣告 const todos = [];

2.error.js
<br>
⭐ import errHandle from './errorHandle.js';

3.errorHandle.js
<br>
⭐ export default errorHandle; 

4.dele.js
<br>
⭐ 需要先寫刪除單筆的狀況，再寫刪除全部的狀況<br>
🔴 不然執行下來會都是刪除全部

**需要調整 "type": "module"**<br>
import http from 'http';<br>
import { v4 as uuidv4 } from "uuid";<br>
import errHandle from './errorHandle.js';

**注意 res.end(); 的位置**
