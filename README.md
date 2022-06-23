# react-override-props

可以覆盖原有的 `React.DetailedHTMLProps` 属性的常用 HTML props


```tsx
import { DivProps } from "react-override-props";

export type UxCheckboxProps = DivProps<{
  value?: boolean;
  onChange?: (selected: boolean) => void;
}>;

```