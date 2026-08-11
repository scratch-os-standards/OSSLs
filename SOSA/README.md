The SOSA-OSSL 3.0 is the latest and greatest version of the OSSL meant to solve the problems of past OSSLs, but there are still some things to clear up about this license.

# Open-Source status
Many previous authors using past versions of the OSSL (especially the SCA-OSSL 1.0) mistakenly called it "open-source" or "FOSS," which is legally incorrect. This is because all OSSLs before 3.0 featured a clause that restricted the sale of the unmodified version of the software, which violates the Open Source Initiative's definition of Open Source software, along with the GNU Foundation's definition of Free Software.

## SOSA-OSSL 3.0 alone
The SOSA-OSSL is intended to comply with the Open Source Definition and qualify as Free Software under the four freedoms, so for most practical purposes, it can be referred to as a FOSS (Free and Open-source) software license. It is still important to note that the SOSA-OSSL v3.0, or any OSSL, has not been reviewed by the OSI.

## SOSA-OSSL 3.0 + OCDA
The OCDA is a clause that restores the restriction on commercial redistribution as seen in previous OSSLs. This makes software that uses the OCDA not open-source. Instead, you may refer to it as "Source-available" or other similar terms.

## SCA-OSSL 1.0, SCA-DT-OSSL 1.x, DT-OSSL 2.0 and DT-OSSL 2.1
These are past OSSLs that include the clause to restrict commercial redistribution and therefore are not free or open-source.

# Which to choose?
```
Is your software under the SCA-OSSL, SCA-DT-OSSL, or DT-OSSL?
-> Do you want to retain similar rights and conditions with your current license?
  -> SOSA-OSSL 3.0 + OCDA (Adds copyleft, retains commercial redistribution restriction, not FOSS)
-> Do you want your software to be licensed under an OSI-compliant license?
  -> SOSA-OSSL (Adds copyleft, drops commercial redistribution restriction, is FOSS)

Is your software currently under an OSI-compliant license, or are you making a new project?
-> Do you want to remain/make your software licensed under an OSI-compliant license?
  -> SOSA-OSSL 3.0
-> Are you worried about people profiting off of your work without your knowledge?
  -> SOSA-OSSL 3.0 + OCDA (must request permission before commercially redistributing, not FOSS)
```
