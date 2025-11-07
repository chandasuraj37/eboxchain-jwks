# eboxchain-jwks

This repository contains JSON Web Key Set (JWKS) configuration for eboxchain.

## Files

- `jwks.json` - Contains the public keys used for JWT signature verification
- `index_new.html` - Web interface for the JWKS service

## Usage

The JWKS endpoint provides public keys that can be used to verify JWT tokens signed by the eboxchain service.

### Accessing the JWKS

You can access the JWKS data directly from the `jwks.json` file or through the web interface.

## Security

This repository contains only public keys and is safe to be publicly accessible.
