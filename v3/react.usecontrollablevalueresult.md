<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [react](./react.md) &gt; [UseControllableValueResult](./react.usecontrollablevalueresult.md)

## UseControllableValueResult type

<b>Signature:</b>

```typescript
export declare type UseControllableValueResult<TProps, TValuePropName extends keyof TProps, TCallbackPropName extends keyof TProps, TDefaultValue extends TProps[TValuePropName]> = [TDefaultValue extends undefined ? TProps[TValuePropName] : Defined<TProps[TValuePropName]>, Defined<TProps[TCallbackPropName]>];
```