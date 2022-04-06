### BSN-DDC Portal OpenAPI Instructions
OpenAPI is a set of BSN-DDC management service interfaces opened by BSNDA for Platform Owners, which does not include "Service Activation" and "Billing account recharge/withdrawal" operations in the BSN-DDC Portal (ddc.bsnbase.com).

BSNDA recommends Platform Owners to follow the "BSN-DDCPortal OpenAPI.pdf" file for interfacing, and they can integrate the management  functions and query functions of the BSN-DDC into their own business portal. The server side will verify the validity of the apitoken value and associate the request message to the corresponding platform according to this value.

For the gateway URL and apitoken value, please visit ddc.bsnbase.com and find them in 【Service Activation】.


