<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [PhoneAuthProvider](./auth-types.phoneauthprovider.md)

## PhoneAuthProvider class

A provider for generating phone credentials.

<b>Signature:</b>

```typescript
export class PhoneAuthProvider implements AuthProvider 
```
<b>Implements:</b> [AuthProvider](./auth-types.authprovider.md)

## Example


```javascript
// 'recaptcha-container' is the ID of an element in the DOM.
const applicationVerifier = new RecaptchaVerifier('recaptcha-container');
const provider = new PhoneAuthProvider(auth);
const verificationId = await provider.verifyPhoneNumber('+16505550101', applicationVerifier);
const verificationCode = window.prompt('Please enter the verification code that was sent to your mobile device.');
const phoneCredential = await PhoneAuthProvider.credential(verificationId, verificationCode);
const userCredential = await signInWithCredential(auth, phoneCredential);

```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(auth)](./auth-types.phoneauthprovider._constructor_.md) |  | Constructs a new instance of the <code>PhoneAuthProvider</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [PHONE\_SIGN\_IN\_METHOD](./auth-types.phoneauthprovider.phone_sign_in_method.md) | <code>static</code> | [SignInMethod](./auth-types.signinmethod.md) | Always set to [SignInMethod.PHONE](./auth-types.signinmethod.phone.md)<!-- -->. |
|  [PROVIDER\_ID](./auth-types.phoneauthprovider.provider_id.md) | <code>static</code> | [ProviderId](./auth-types.providerid.md) | Always set to [ProviderId.PHONE](./auth-types.providerid.phone.md)<!-- -->. |
|  [providerId](./auth-types.phoneauthprovider.providerid.md) |  | [ProviderId](./auth-types.providerid.md) | Always set to [ProviderId.PHONE](./auth-types.providerid.phone.md)<!-- -->. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [credential(verificationId, verificationCode)](./auth-types.phoneauthprovider.credential.md) | <code>static</code> | Creates a phone auth credential, given the verification ID from [PhoneAuthProvider.verifyPhoneNumber()](./auth-types.phoneauthprovider.verifyphonenumber.md) and the code that was sent to the user's mobile device. |
|  [verifyPhoneNumber(phoneInfoOptions, applicationVerifier)](./auth-types.phoneauthprovider.verifyphonenumber.md) |  | Starts a phone number authentication flow by sending a verification code to the given phone number. Returns an ID that can be passed to [PhoneAuthProvider.credential()](./auth-types.phoneauthprovider.credential.md) to identify this flow. |

