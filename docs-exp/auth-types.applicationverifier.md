<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [ApplicationVerifier](./auth-types.applicationverifier.md)

## ApplicationVerifier interface

A verifier for domain verification and abuse prevention. Currently, the only implementation is [RecaptchaVerifier](./auth-types.recaptchaverifier.md)<!-- -->.

<b>Signature:</b>

```typescript
export interface ApplicationVerifier 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [type](./auth-types.applicationverifier.type.md) | string | Identifies the type of application verifier (e.g. "recaptcha"). |

## Methods

|  Method | Description |
|  --- | --- |
|  [verify()](./auth-types.applicationverifier.verify.md) | Executes the verification process. |

