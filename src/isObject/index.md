
# isObject


### 源码

```jsx
/**
 * compact: true
 */

const isObject= (value: any): boolean => {
  const type = typeof value;
  return value != null && (type === 'object' || type === 'function');
};
export default isObject;
```