<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth](./auth.md)

## auth package

## Classes

|  Class | Description |
|  --- | --- |
|  [ActionCodeURL](./auth.actioncodeurl.md) | A utility class to parse email action URLs such as password reset, email verification, email link sign in, etc. |
|  [AuthCredential](./auth.authcredential.md) |  |
|  [EmailAuthCredential](./auth.emailauthcredential.md) |  |
|  [EmailAuthProvider](./auth.emailauthprovider.md) |  |
|  [FacebookAuthProvider](./auth.facebookauthprovider.md) |  |
|  [GithubAuthProvider](./auth.githubauthprovider.md) |  |
|  [GoogleAuthProvider](./auth.googleauthprovider.md) |  |
|  [OAuthCredential](./auth.oauthcredential.md) |  |
|  [OAuthProvider](./auth.oauthprovider.md) |  |
|  [PhoneAuthCredential](./auth.phoneauthcredential.md) |  |
|  [PhoneAuthProvider](./auth.phoneauthprovider.md) |  |
|  [PhoneMultiFactorGenerator](./auth.phonemultifactorgenerator.md) |  |
|  [RecaptchaVerifier](./auth.recaptchaverifier.md) |  |
|  [TwitterAuthProvider](./auth.twitterauthprovider.md) |  |

## Functions

|  Function | Description |
|  --- | --- |
|  [applyActionCode(auth, oobCode)](./auth.applyactioncode.md) |  |
|  [checkActionCode(auth, oobCode)](./auth.checkactioncode.md) |  |
|  [confirmPasswordReset(auth, oobCode, newPassword)](./auth.confirmpasswordreset.md) |  |
|  [createUserWithEmailAndPassword(auth, email, password)](./auth.createuserwithemailandpassword.md) |  |
|  [deleteUser(user)](./auth.deleteuser.md) |  |
|  [fetchSignInMethodsForEmail(auth, email)](./auth.fetchsigninmethodsforemail.md) |  |
|  [getAdditionalUserInfo(userCredential)](./auth.getadditionaluserinfo.md) |  |
|  [getAuth(app)](./auth.getauth.md) |  |
|  [getIdToken(user, forceRefresh)](./auth.getidtoken.md) |  |
|  [getIdTokenResult(externUser, forceRefresh)](./auth.getidtokenresult.md) |  |
|  [getMultiFactorResolver(auth, errorExtern)](./auth.getmultifactorresolver.md) |  |
|  [getRedirectResult(authExtern, resolverExtern)](./auth.getredirectresult.md) |  |
|  [initializeAuth(app, deps)](./auth.initializeauth.md) |  |
|  [isSignInWithEmailLink(auth, emailLink)](./auth.issigninwithemaillink.md) |  |
|  [linkWithCredential(userExtern, credentialExtern)](./auth.linkwithcredential.md) |  |
|  [linkWithPhoneNumber(userExtern, phoneNumber, appVerifier)](./auth.linkwithphonenumber.md) |  |
|  [linkWithPopup(userExtern, provider, resolverExtern)](./auth.linkwithpopup.md) |  |
|  [linkWithRedirect(userExtern, provider, resolverExtern)](./auth.linkwithredirect.md) |  |
|  [multiFactor(user)](./auth.multifactor.md) |  |
|  [onAuthStateChanged(auth, nextOrObserver, error, completed)](./auth.onauthstatechanged.md) |  |
|  [onIdTokenChanged(auth, nextOrObserver, error, completed)](./auth.onidtokenchanged.md) |  |
|  [parseActionCodeURL(link)](./auth.parseactioncodeurl.md) | Parses the email action link string and returns an ActionCodeURL object if the link is valid, otherwise returns null. |
|  [reauthenticateWithCredential(userExtern, credentialExtern)](./auth.reauthenticatewithcredential.md) |  |
|  [reauthenticateWithPhoneNumber(userExtern, phoneNumber, appVerifier)](./auth.reauthenticatewithphonenumber.md) |  |
|  [reauthenticateWithPopup(userExtern, provider, resolverExtern)](./auth.reauthenticatewithpopup.md) |  |
|  [reauthenticateWithRedirect(userExtern, provider, resolverExtern)](./auth.reauthenticatewithredirect.md) |  |
|  [reload(externUser)](./auth.reload.md) |  |
|  [sendEmailVerification(userExtern, actionCodeSettings)](./auth.sendemailverification.md) |  |
|  [sendPasswordResetEmail(auth, email, actionCodeSettings)](./auth.sendpasswordresetemail.md) |  |
|  [sendSignInLinkToEmail(auth, email, actionCodeSettings)](./auth.sendsigninlinktoemail.md) |  |
|  [setPersistence(auth, persistence)](./auth.setpersistence.md) |  |
|  [signInAnonymously(auth)](./auth.signinanonymously.md) |  |
|  [signInWithCredential(auth, credential)](./auth.signinwithcredential.md) |  |
|  [signInWithCustomToken(authExtern, customToken)](./auth.signinwithcustomtoken.md) |  |
|  [signInWithEmailAndPassword(auth, email, password)](./auth.signinwithemailandpassword.md) |  |
|  [signInWithEmailLink(auth, email, emailLink)](./auth.signinwithemaillink.md) |  |
|  [signInWithPhoneNumber(auth, phoneNumber, appVerifier)](./auth.signinwithphonenumber.md) |  |
|  [signInWithPopup(authExtern, provider, resolverExtern)](./auth.signinwithpopup.md) |  |
|  [signInWithRedirect(authExtern, provider, resolverExtern)](./auth.signinwithredirect.md) |  |
|  [signOut(auth)](./auth.signout.md) |  |
|  [unlink(userExtern, providerId)](./auth.unlink.md) | This is the externally visible unlink function |
|  [updateCurrentUser(auth, user)](./auth.updatecurrentuser.md) |  |
|  [updateEmail(externUser, newEmail)](./auth.updateemail.md) |  |
|  [updatePassword(externUser, newPassword)](./auth.updatepassword.md) |  |
|  [updatePhoneNumber(user, credential)](./auth.updatephonenumber.md) |  |
|  [updateProfile(externUser, { displayName, photoURL: photoUrl })](./auth.updateprofile.md) |  |
|  [useDeviceLanguage(auth)](./auth.usedevicelanguage.md) |  |
|  [verifyBeforeUpdateEmail(userExtern, newEmail, actionCodeSettings)](./auth.verifybeforeupdateemail.md) |  |
|  [verifyPasswordResetCode(auth, code)](./auth.verifypasswordresetcode.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [browserLocalPersistence](./auth.browserlocalpersistence.md) |  |
|  [browserPopupRedirectResolver](./auth.browserpopupredirectresolver.md) |  |
|  [browserSessionPersistence](./auth.browsersessionpersistence.md) |  |
|  [indexedDBLocalPersistence](./auth.indexeddblocalpersistence.md) |  |
|  [inMemoryPersistence](./auth.inmemorypersistence.md) |  |

