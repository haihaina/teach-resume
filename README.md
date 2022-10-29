## 交互
结合其他库使用才能生效

```
pnpx astro add solid 
```



下载完成之后在我们的astro.config.mjs里面就有了我们的引入

```javascript
import { defineConfig } from 'astro/config';

// https://astro.build/config
import solidJs from "@astrojs/solid-js";

// https://astro.build/config
export default defineConfig({
  integrations: [solidJs()]
});
```

引入好之后可以直接将我们的后缀改成tsx格式。