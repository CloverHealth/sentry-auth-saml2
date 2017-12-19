# SAML2 Auth for Sentry Clover Fork

*NOTE:* The Upstream [MANIFEST.in](https://github.com/getsentry/sentry-auth-saml2/master/MANIFEST.in) is behind we should make a PR to upstream.  

*Note:* SAML2 Authenttication is still currently an experimental feature.

An SSO provider for Sentry which enables SAML SSO and SLO support, including
various identity provider support.

The following identity providers are supported

 * [OneLogin](https://www.onelogin.com/)
 * [Okta](https://www.okta.com/)
 * [Auth0](https://auth0.com/)
 * [Rippling](https://rippling.com/)

A generic SAML2 module is also provided, which may be configured with any
Identity Provider that conforms to the SAML2 specification.

## Install

```
$ pip install https://github.com/getsentry/sentry-auth-saml2/archive/master.zip
```
Check the [requirements.txt](https://github.com/CloverHealth/sentry_onpremise/blob/master/requirements.txt#L2) in the sentry_onpremise repo. 

## Configuration

Refer to the Sentry [Single Sign-On
documentation](https://docs.sentry.io/learn/sso/) for individual SAML Identity
Provider configurations.

## Troubleshooting

 * check that the [sentry_auth_saml2](https://github.com/CloverHealth/sentry-auth-saml2) plugin is in [requirements.txt](https://github.com/CloverHealth/sentry_onpremise/blob/master/requirements.txt#L2) 
 * Review the [MANIFEST.in](https://github.com/CloverHealth/sentry-auth-saml2/master/MANIFEST.in) file reflects the current master branch
