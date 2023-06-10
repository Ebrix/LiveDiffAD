Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.
                                                                                                                        Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows                                                                                                                                                       PS C:\Users\Administrator> cd .\Desktop\                                                                                PS C:\Users\Administrator\Desktop> .\LAMInstaller.exe -installADM^C                                                     PS C:\Users\Administrator\Desktop> .\livediff.ps1
PS C:\Users\Administrator\Desktop> ipmo .\livediff.ps1
PS C:\Users\Administrator\Desktop> Show-LiveDiff
[06/10/2023 03:55:41] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 03:55:44] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 03:55:44] CN=RID Set,CN=DC1,OU=Domain Controllers,DC=dom,DC=local

        objectCategory: CN=RID-Set,CN=Schema,CN=Configuration,DC=dom,DC=local
        rIDUsedPool: 0
        rIDAllocationPool: 6867652707404
        name: RID Set
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;CIID;CCDC;bf967aba-0de6-11d0-a285-00aa003049e2;;BU)(OA;CIIOID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;bf967aba-0de6-11d0-a285-00aa003049e2;BU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        showInAdvancedViewOnly: True
        whenCreated: 02/22/2023 08:22:04
        instanceType: 4
        cn: RID Set
        objectClass: rIDSet
[06/10/2023 03:55:44] CN=ADCS,CN=Computers,DC=dom,DC=local

        lastLogonTimestamp: 133308681415727486
        isCriticalSystemObject: False
        objectCategory: CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local
        servicePrincipalName: RestrictedKrbHost/ADCS HOST/ADCS RestrictedKrbHost/ADCS.dom.local HOST/ADCS.dom.local
        dNSHostName: ADCS.dom.local
        operatingSystemVersion: 10.0 (14393)
        operatingSystem: Windows Server 2016 Standard
        sAMAccountType: SAM_MACHINE_ACCOUNT
        sAMAccountName: ADCS$
        lmPwdHistory:
        accountExpires: 9223372036854775807
        objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109
        supplementalCredentials:
        primaryGroupID: 515
        pwdLastSet: 133308681413222936
        ntPwdHistory:
        unicodePwd:
        logonHours:
        localPolicyFlags: 0
        dBCSPwd:
        countryCode: 0
        codePage: 0
        userAccountControl: UF_WORKSTATION_TRUST_ACCOUNT
        name: ADCS
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        whenCreated: 06/10/2023 03:55:41
        instanceType: 4
        cn: ADCS
        objectClass: computer
[06/10/2023 03:55:44] CN=ADCS,CN=Computers,DC=dom,DC=local

        lastLogonTimestamp: 133308681415727486
        isCriticalSystemObject: False
        objectCategory: CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local
        servicePrincipalName: RestrictedKrbHost/ADCS HOST/ADCS RestrictedKrbHost/ADCS.dom.local HOST/ADCS.dom.local
        dNSHostName: ADCS.dom.local
        operatingSystemVersion: 10.0 (14393)
        operatingSystem: Windows Server 2016 Standard
        sAMAccountType: SAM_MACHINE_ACCOUNT
        sAMAccountName: ADCS$
        lmPwdHistory:
        accountExpires: 9223372036854775807
        objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109
        supplementalCredentials:
        primaryGroupID: 515
        pwdLastSet: 133308681413222936
        ntPwdHistory:
        unicodePwd:
        logonHours:
        localPolicyFlags: 0
        dBCSPwd:
        countryCode: 0
        codePage: 0
        userAccountControl: UF_WORKSTATION_TRUST_ACCOUNT
        name: ADCS
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        whenCreated: 06/10/2023 03:55:41
        instanceType: 4
        cn: ADCS
        objectClass: computer
[06/10/2023 03:55:44] CN=ADCS,CN=Computers,DC=dom,DC=local

        lastLogonTimestamp: 133308681415727486
        isCriticalSystemObject: False
        objectCategory: CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local
        servicePrincipalName: RestrictedKrbHost/ADCS HOST/ADCS RestrictedKrbHost/ADCS.dom.local HOST/ADCS.dom.local
        dNSHostName: ADCS.dom.local
        operatingSystemVersion: 10.0 (14393)
        operatingSystem: Windows Server 2016 Standard
        sAMAccountType: SAM_MACHINE_ACCOUNT
        sAMAccountName: ADCS$
        lmPwdHistory:
        accountExpires: 9223372036854775807
        objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109
        supplementalCredentials:
        primaryGroupID: 515
        pwdLastSet: 133308681413222936
        ntPwdHistory:
        unicodePwd:
        logonHours:
        localPolicyFlags: 0
        dBCSPwd:
        countryCode: 0
        codePage: 0
        userAccountControl: UF_WORKSTATION_TRUST_ACCOUNT
        name: ADCS
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        whenCreated: 06/10/2023 03:55:41
        instanceType: 4
        cn: ADCS
        objectClass: computer
[06/10/2023 03:55:44] CN=ADCS,CN=Computers,DC=dom,DC=local

        lastLogonTimestamp: 133308681415727486
        isCriticalSystemObject: False
        objectCategory: CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local
        servicePrincipalName: RestrictedKrbHost/ADCS HOST/ADCS RestrictedKrbHost/ADCS.dom.local HOST/ADCS.dom.local
        dNSHostName: ADCS.dom.local
        operatingSystemVersion: 10.0 (14393)
        operatingSystem: Windows Server 2016 Standard
        sAMAccountType: SAM_MACHINE_ACCOUNT
        sAMAccountName: ADCS$
        lmPwdHistory:
        accountExpires: 9223372036854775807
        objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109
        supplementalCredentials:
        primaryGroupID: 515
        pwdLastSet: 133308681413222936
        ntPwdHistory:
        unicodePwd:
        logonHours:
        localPolicyFlags: 0
        dBCSPwd:
        countryCode: 0
        codePage: 0
        userAccountControl: UF_WORKSTATION_TRUST_ACCOUNT
        name: ADCS
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        whenCreated: 06/10/2023 03:55:41
        instanceType: 4
        cn: ADCS
        objectClass: computer
[06/10/2023 03:55:44] CN=ADCS,CN=Computers,DC=dom,DC=local

        lastLogonTimestamp: 133308681415727486
        isCriticalSystemObject: False
        objectCategory: CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local
        servicePrincipalName: RestrictedKrbHost/ADCS HOST/ADCS RestrictedKrbHost/ADCS.dom.local HOST/ADCS.dom.local
        dNSHostName: ADCS.dom.local
        operatingSystemVersion: 10.0 (14393)
        operatingSystem: Windows Server 2016 Standard
        sAMAccountType: SAM_MACHINE_ACCOUNT
        sAMAccountName: ADCS$
        lmPwdHistory:
        accountExpires: 9223372036854775807
        objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109
        supplementalCredentials:
        primaryGroupID: 515
        pwdLastSet: 133308681413222936
        ntPwdHistory:
        unicodePwd:
        logonHours:
        localPolicyFlags: 0
        dBCSPwd:
        countryCode: 0
        codePage: 0
        userAccountControl: UF_WORKSTATION_TRUST_ACCOUNT
        name: ADCS
        nTSecurityDescriptor: O:DAG:DAD:AI(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        whenCreated: 06/10/2023 03:55:41
        instanceType: 4
        cn: ADCS
        objectClass: computer
[06/10/2023 03:56:10] DC=ADCS,DC=dom.local,CN=MicrosoftDNS,DC=DomainDnsZones,DC=dom,DC=local

        dc: ADCS
        objectCategory: CN=Dns-Node,CN=Schema,CN=Configuration,DC=dom,DC=local
        dnsRecord: 4 0 1 0 5 240 0 0 79 0 0 0 0 0 4 176 0 0 0 0 234 128 56 0 10 1 0 12
        name: ADCS
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-1109G:DCD:AI(A;;LCRPLORC;;;WD)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;ED)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;CIID;CCDCLCSWRPWPDTCRSDRCWDWO;;;ED)(A;CIID;CCDCLCSWRPWPDTCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1101)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)
        showInAdvancedViewOnly: True
        whenCreated: 06/10/2023 03:56:09
        instanceType: 4
        objectClass: dnsNode
[06/10/2023 03:56:11] CN=ADCS,CN=Computers,DC=dom,DC=local

        msDS-SupportedEncryptionTypes: RC4_HMAC_MD5, AES128_CTS_HMAC_SHA1_96, AES256_CTS_HMAC_SHA1_96
[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 03:57:11] CN=AdminSDHolder,CN=System,DC=dom,DC=local

[Summary - DC=dom,DC=local]
Using cookie from file cookie.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

Objects returned: 1

(0) add CN=ADCS,CN=Computers,DC=dom,DC=local

    1> parentGUID: acc3a1ad-078f-4d8a-affb-75d02852603b

    1> objectGUID: 59ca083a-0025-4b49-a421-d078cb478ec3

    5> objectClass: top; person; organizationalPerson; user; computer

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 3:55:41 AM Pacific Daylight Time

    1> nTSecurityDescriptor: O:DAG:DAD:AI(OA;;WP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967950-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;bf967953-0de6-11d0-a285-00aa003049e2;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;WP;3e0abfd0-126a-11d0-a060-00aa006c33ed;bf967a86-0de6-11d0-a285-00aa003049e2;DA)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;DA)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;DA)(OA;;WP;4c164200-20c0-11d0-a768-00aa006e0529;;DA)(OA;;RPWP;bf967a7f-0de6-11d0-a285-00aa003049e2;;CA)(OA;;CCDC;bf967aa8-0de6-11d0-a285-00aa003049e2;;PO)(OA;;RP;46a9b11d-60ae-405a-b7e8-ff8a58d456d2;;S-1-5-32-560)(OA;;CR;ab721a53-1e2f-11d0-9819-00aa0040529b;;WD)(OA;;SW;72e39547-7b18-11d1-adef-00c04fd8d5cd;;PS)(OA;;SW;f3a64788-5306-11d1-a9c5-0000f80367c1;;PS)(OA;;RPWP;77b5b886-944a-11d1-aebd-0000f80367c1;;PS)(A;;LCRPDTLOCRSDRC;;;DA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;AO)(A;;CCDC;;;PS)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-526)(OA;CIID;RPWP;5b47d60f-6090-40b2-9f37-2a4de88f3063;;S-1-5-21-1047456448-2337630968-2720937775-527)(OA;ID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;;DA)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)S:AI(OU;CIIOIDSA;WP;f30e3bbe-9ff0-11d1-b603-0000f80367c1;bf967aa5-0de6-11d0-a285-00aa003049e2;WD)(OU;CIIOIDSA;WP;f30e3bbf-9ff0-11d1-b603-0000f80367c1;bf967aa5-0de6-11d0-a285-00aa003049e2;WD)

    1> name: ADCS

    1> userAccountControl: 0x1000 = ( WORKSTATION_TRUST_ACCOUNT )

    1> codePage: 0

    1> countryCode: 0

    0> dBCSPwd:

    1> localPolicyFlags: 0

    0> logonHours:

    0> unicodePwd:

    0> ntPwdHistory:

    1> pwdLastSet: 6/10/2023 3:55:41 AM Pacific Daylight Time

    1> primaryGroupID: 515 = ( GROUP_RID_COMPUTERS )

    0> supplementalCredentials:

    1> objectSid: S-1-5-21-1047456448-2337630968-2720937775-1109

    1> accountExpires: (never)

    0> lmPwdHistory:

    1> sAMAccountName: ADCS$

    1> sAMAccountType: 805306369 = ( MACHINE_ACCOUNT )

    1> operatingSystem: Windows Server 2016 Standard

    1> operatingSystemVersion: 10.0 (14393)

    1> dNSHostName: ADCS.dom.local

    4> servicePrincipalName: RestrictedKrbHost/ADCS; HOST/ADCS; RestrictedKrbHost/ADCS.dom.local; HOST/ADCS.dom.local

    1> objectCategory: <GUID=7b2b766dddd4b24c8f688bdd11598ed9>;CN=Computer,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> isCriticalSystemObject: FALSE

    1> lastLogonTimestamp: 6/10/2023 3:55:41 AM Pacific Daylight Time

    1> msDS-SupportedEncryptionTypes: 0x1C = ( RC4_HMAC_MD5 | AES128_CTS_HMAC_SHA1_96 | AES256_CTS_HMAC_SHA1_96 )

New cookie written to file cookie.bin (108 bytes)



[Summary - CN=Configuration,DC=dom,DC=local]
Using cookie from file cookie-config.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

No Changes

New cookie written to file cookie-config.bin (108 bytes)



[Summary - CN=Schema,CN=Configuration,DC=dom,DC=local]
Using cookie from file cookie-schema.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

No Changes

New cookie written to file cookie-schema.bin (108 bytes)



[Summary - DC=ForestDnsZones,DC=dom,DC=local]
Using cookie from file cookie-forestdns.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

No Changes

New cookie written to file cookie-forestdns.bin (108 bytes)



[Summary - DC=DomainDnsZones,DC=dom,DC=local]
Using cookie from file cookie-domaindns.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

Objects returned: 1

(0) add DC=ADCS,DC=dom.local,CN=MicrosoftDNS,DC=DomainDnsZones,DC=dom,DC=local

    1> parentGUID: 1c0074e9-ef0b-4e35-8d18-04e3ccb5a535

    1> objectGUID: e90e5261-6281-4410-a670-ccf63f4e881d

    2> objectClass: top; dnsNode

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 3:56:09 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-1109G:DCD:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;;LCRPLORC;;;WD)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;ED)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTCRSDRCWDWO;;;ED)(A;CIID;CCDCLCSWRPWPDTCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1101)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;4c164200-20c0-11d0-a768-00aa006e0529;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;5f202010-79a5-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;bc0ac240-79a9-11d0-9020-00c04fc2d4cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;59ba2f42-79a2-11d0-9020-00c04fc2d3cf;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;RP;037088f8-0ae1-11d2-b422-00a0c968f939;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;CO)(OA;CIIOID;SW;9b026da6-0d3c-465c-8bee-5199d7165cba;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a86-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967a9c-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;RP;b7c69e6d-2cc7-11d2-854e-00a0c983f608;bf967aba-0de6-11d0-a285-00aa003049e2;ED)(OA;CIIOID;WP;ea1b7b93-5e48-46d5-bc6c-4df4fda78a35;bf967a86-0de6-11d0-a285-00aa003049e2;PS)(OA;CIIOID;LCRPLORC;;4828cc14-1437-45bc-9b07-ad6f015e5f28;RU)(OA;CIIOID;LCRPLORC;;bf967a9c-0de6-11d0-a285-00aa003049e2;RU)(OA;CIIOID;LCRPLORC;;bf967aba-0de6-11d0-a285-00aa003049e2;RU)(OA;OICIID;RPWP;3f78c3e5-f79a-46bd-a0b8-9d18116ddc79;;PS)(OA;CIID;RPWPCR;91e647de-d96f-4b70-9557-d63ff4f3ccd8;;PS)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;LC;;;RU)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;BA)S:AI(OU;CIIOIDSA;WP;f30e3bbe-9ff0-11d1-b603-0000f80367c1;bf967aa5-0de6-11d0-a285-00aa003049e2;WD)(OU;CIIOIDSA;WP;f30e3bbf-9ff0-11d1-b603-0000f80367c1;bf967aa5-0de6-11d0-a285-00aa003049e2;WD)

    1> name: ADCS

    1> dnsRecord: <28 byte blob>

    1> objectCategory: <GUID=8cdb83b12ffba846a04e897fcd652c26>;CN=Dns-Node,CN=Schema,CN=Configuration,DC=dom,DC=local

New cookie written to file cookie-domaindns.bin (108 bytes)



PS C:\Users\Administrator\Desktop> dir


    Directory: C:\Users\Administrator\Desktop


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         6/14/2021   1:36 AM           2377 config-oradad.xml
-a----         6/10/2023   3:57 AM            108 cookie-config.bin
-a----         6/10/2023   3:57 AM            108 cookie-domaindns.bin
-a----         6/10/2023   3:57 AM            108 cookie-forestdns.bin
-a----         6/10/2023   3:57 AM            108 cookie-schema.bin
-a----         6/10/2023   3:57 AM            108 cookie.bin
-a----         2/23/2023   7:24 AM          17785 livediff.ps1
-a----         7/12/2022  12:18 AM        2540032 ORADAD.exe
-a----         5/31/2023   1:17 AM          33402 oradad.log
-a----         2/23/2023   8:33 AM           2167 README.md


PS C:\Users\Administrator\Desktop> del .\cookie*
PS C:\Users\Administrator\Desktop> dir


    Directory: C:\Users\Administrator\Desktop


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         6/14/2021   1:36 AM           2377 config-oradad.xml
-a----         2/23/2023   7:24 AM          17785 livediff.ps1
-a----         7/12/2022  12:18 AM        2540032 ORADAD.exe
-a----         5/31/2023   1:17 AM          33402 oradad.log
-a----         2/23/2023   8:33 AM           2167 README.md


PS C:\Users\Administrator\Desktop>
PS C:\Users\Administrator\Desktop> Show-LiveDiff
[06/10/2023 03:59:31] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:00:35] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:01:39] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:02:44] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:02:49] DC=dc1,DC=dom.local,CN=MicrosoftDNS,DC=DomainDnsZones,DC=dom,DC=local

        dnsRecord: System.Byte[] System.Byte[]
[06/10/2023 04:03:02] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:03:02] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:03:47] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:04:02] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:04:51] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:05:54] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:06:38] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:06:43] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:06:59] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:07:25] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:07:28] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:08:00] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:08:03] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:08:03] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:08:03] CN=Administrator,CN=Users,DC=dom,DC=local

        lastLogonTimestamp: 133308688826119961
[06/10/2023 04:08:47] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:08:51] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:07] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:09:13] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:14] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:24] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:28] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:35] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:09:35] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:10:13] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:10:15] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:10:16] CN=dom-ADCS-CA,CN=Certification Authorities,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        objectCategory: CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local
        name: dom-ADCS-CA
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;LCRPLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;CA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        whenCreated: 06/10/2023 04:10:16
        instanceType: 4
        certificateRevocationList: 0
        authorityRevocationList: 0
        cACertificate: 48 130 5 97 48 130 3 73 160 3 2 1 2 2 16 93 212 246 88 235 9 51 159 66 71 65 30 225 249 44 9 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 32 23 13 50 51 48 54 49 48 49 49 48 48 49 52 90 24 15 50 53 50 51 48 54 49 48 49 49 49 48 49 51 90 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 130 2 34 48 13 6 9 42 134 72 134 247 13 1 1 1 5 0 3 130 2 15 0 48 130 2 10 2 130 2 1 0 181 2 9 55 210 51 28 20 186 211 235 52 238 4 84 248 182 42 50 116 31 96 48 40 12 19 99 84 133 171 213 133 153 163 41 53 36 45 106 156 8 93 188 90 19 100 251 254 195 48 225 189 49 34 129 242 9 211 68 5 137 71 47 50 101 1 185 109 75 29 1 203 181 63 165 84 206 207 13 168 25 17 107 208 192 220 100 103 46 252 249 248 111 85 182 74 156 139 134 36 28 37 126 213 79 220 37 14 84 120 93 84 175 62 169 100 67 17 138 109 71 252 242 88 120 95 43 193 46 178 23 202 118 102 253 232 254 134 228 99 40 145 66 117 104 78 163 106 160 203 224 80 18 230 138 111 166 189 107 199 199 141 97 95 157 111 28 163 159 1 221 234 112 48 238 27 128 171 15 74 100 56 62 4 187 249 163 99 184 134 108 231 137 26 17 78 248 196 178 161 142 232 251 92 51 244 166 99 251 16 43 132 20 210 197 96 148 145 81 44 44 11 51 38 117 216 160 253 193 55 198 48 202 152 15 146 221 39 174 39 6 90 99 163 194 181 172 19 84 166 34 69 255 40 148 35 99 137 141 133 43 37 184 96 98 83 89 119 245 227 213 160 115 198 92 175 100 73 54 108 145 143 215 22 81 24 170 44 104 60 225 218 174 210 142 148 230 219 38 119 225 194 112 51 8 123 58 212 189 61 73 26 101 25 132 78 33 130 246 228 48 225 104 157 193 42 129 48 216 23 40 77 32 78 88 131 25 165 206 51 5 218 248 118 224 102 211 81 78 180 88 91 247 46 56 173 105 120 106 101 223 92 116 107 201 183 54 192 26 24 100 167 143 182 192 194 32 26 184 22 50 200 81 121 199 48 118 246 82 41 135 58 76 31 195 158 148 66 157 43 177 192 79 198 15 25 74 99 3 191 232 6 207 129 165 168 134 222 217 38 254 158 74 165 168 68 10 247 17 132 56 175 47 143 0 140 162 229 5 63 109 197 57 74 76 166 83 141 222 42 176 240 43 252 46 222 255 8 38 217 212 248 110 240 60 236 175 246 206 27 210 93 33 28 39 18 154 127 90 187 99 41 219 78 132 137 235 103 94 215 119 0 5 145 187 166 88 131 204 255 173 124 148 182 47 28 74 31 181 58 51 131 2 3 1 0 1 163 81 48 79 48 11 6 3 85 29 15 4 4 3 2 1 134 48 15 6 3 85 29 19 1 1 255 4 5 48 3 1 1 255 48 29 6 3 85 29 14 4 22 4 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 30 168 151 68 111 100 174 115 190 33 77 154 53 195 95 110 166 42 36 52 239 27 13 14 49 240 18 143 190 59 136 109 59 68 77 63 173 208 89 131 188 70 68 203 71 235 88 130 21 33 202 66 10 100 59 161 233 70 84 251 183 43 167 237 178 60 184 185 63 36 87 77 105 62 75 135 159 225 74 96 61 49 159 53 198 91 177 75 223 179 21 221 40 181 155 53 146 204 70 251 69 243 53 101 233 111 88 125 145 79 184 227 157 172 123 91 198 197 239 97 21 10 59 155 206 24 246 111 30 69 164 126 201 221 122 191 94 58 90 97 84 123 210 248 136 37 72 147 96 240 177 254 104 14 215 215 253 169 85 44 87 240 115 146 150 142 88 160 185 126 116 222 204 59 82 184 101 148 93 22 189 118 67 245 163 166 90 110 11 174 127 52 222 239 114 111 195 123 86 227 61 201 38 221 254 11 60 70 141 137 115 47 27 23 181 26 61 237 48 202 198 53 53 179 58 0 205 27 246 30 198 191 236 77 132 163 218 216 70 172 26 94 3 116 5 123 58 180 5 136 6 187 177 17 163 161 215 198 188 92 55 29 27 251 142 216 233 239 38 195 61 8 44 83 100 120 12 126 196 148 140 67 239 18 81 10 37 210 74 240 105 22 59 28 50 207 224 104 3 60 217 29 36 65 248 78 62 10 233 170 126 156 224 252 186 93 249 58 199 223 0 62 88 76 136 142 109 154 190 15 187 132 85 18 112 28 13 253 173 120 96 15 131 202 23 47 21 125 21 81 235 237 177 149 26 24 207 179 157 48 55 93 65 203 133 36 122 251 137 173 171 181 179 134 217 11 205 139 180 120 154 52 253 6 20 120 14 184 200 129 156 192 0 215 245 157 69 147 255 130 59 216 136 187 29 113 105 96 134 98 64 62 248 228 181 134 76 17 120 209 108 171 127 88 62 94 147 143 184 38 39 117 75 233 134 246 137 136 129 212 86 36 16 191 133 120 169 74 31 118 186 202 84 113 22 33 87 211 105 216 83 233 124 143 110 51 83 149 140 181 236 63 96 94 198 205 204 165 180 168 39 186 186 28 103 227 3 150 178 88 136 173 103 188 178 228 117 147 230 197 136 132 23 29 105 49 27 18 180 17 84 57
        cn: dom-ADCS-CA
        objectClass: certificationAuthority
[06/10/2023 04:10:17] CN=NTAuthCertificates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        objectCategory: CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local
        name: NTAuthCertificates
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;LCRPLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        whenCreated: 06/10/2023 04:10:16
        instanceType: 4
        certificateRevocationList: 0
        authorityRevocationList: 0
        cACertificate: 48 130 5 97 48 130 3 73 160 3 2 1 2 2 16 93 212 246 88 235 9 51 159 66 71 65 30 225 249 44 9 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 32 23 13 50 51 48 54 49 48 49 49 48 48 49 52 90 24 15 50 53 50 51 48 54 49 48 49 49 49 48 49 51 90 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 130 2 34 48 13 6 9 42 134 72 134 247 13 1 1 1 5 0 3 130 2 15 0 48 130 2 10 2 130 2 1 0 181 2 9 55 210 51 28 20 186 211 235 52 238 4 84 248 182 42 50 116 31 96 48 40 12 19 99 84 133 171 213 133 153 163 41 53 36 45 106 156 8 93 188 90 19 100 251 254 195 48 225 189 49 34 129 242 9 211 68 5 137 71 47 50 101 1 185 109 75 29 1 203 181 63 165 84 206 207 13 168 25 17 107 208 192 220 100 103 46 252 249 248 111 85 182 74 156 139 134 36 28 37 126 213 79 220 37 14 84 120 93 84 175 62 169 100 67 17 138 109 71 252 242 88 120 95 43 193 46 178 23 202 118 102 253 232 254 134 228 99 40 145 66 117 104 78 163 106 160 203 224 80 18 230 138 111 166 189 107 199 199 141 97 95 157 111 28 163 159 1 221 234 112 48 238 27 128 171 15 74 100 56 62 4 187 249 163 99 184 134 108 231 137 26 17 78 248 196 178 161 142 232 251 92 51 244 166 99 251 16 43 132 20 210 197 96 148 145 81 44 44 11 51 38 117 216 160 253 193 55 198 48 202 152 15 146 221 39 174 39 6 90 99 163 194 181 172 19 84 166 34 69 255 40 148 35 99 137 141 133 43 37 184 96 98 83 89 119 245 227 213 160 115 198 92 175 100 73 54 108 145 143 215 22 81 24 170 44 104 60 225 218 174 210 142 148 230 219 38 119 225 194 112 51 8 123 58 212 189 61 73 26 101 25 132 78 33 130 246 228 48 225 104 157 193 42 129 48 216 23 40 77 32 78 88 131 25 165 206 51 5 218 248 118 224 102 211 81 78 180 88 91 247 46 56 173 105 120 106 101 223 92 116 107 201 183 54 192 26 24 100 167 143 182 192 194 32 26 184 22 50 200 81 121 199 48 118 246 82 41 135 58 76 31 195 158 148 66 157 43 177 192 79 198 15 25 74 99 3 191 232 6 207 129 165 168 134 222 217 38 254 158 74 165 168 68 10 247 17 132 56 175 47 143 0 140 162 229 5 63 109 197 57 74 76 166 83 141 222 42 176 240 43 252 46 222 255 8 38 217 212 248 110 240 60 236 175 246 206 27 210 93 33 28 39 18 154 127 90 187 99 41 219 78 132 137 235 103 94 215 119 0 5 145 187 166 88 131 204 255 173 124 148 182 47 28 74 31 181 58 51 131 2 3 1 0 1 163 81 48 79 48 11 6 3 85 29 15 4 4 3 2 1 134 48 15 6 3 85 29 19 1 1 255 4 5 48 3 1 1 255 48 29 6 3 85 29 14 4 22 4 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 30 168 151 68 111 100 174 115 190 33 77 154 53 195 95 110 166 42 36 52 239 27 13 14 49 240 18 143 190 59 136 109 59 68 77 63 173 208 89 131 188 70 68 203 71 235 88 130 21 33 202 66 10 100 59 161 233 70 84 251 183 43 167 237 178 60 184 185 63 36 87 77 105 62 75 135 159 225 74 96 61 49 159 53 198 91 177 75 223 179 21 221 40 181 155 53 146 204 70 251 69 243 53 101 233 111 88 125 145 79 184 227 157 172 123 91 198 197 239 97 21 10 59 155 206 24 246 111 30 69 164 126 201 221 122 191 94 58 90 97 84 123 210 248 136 37 72 147 96 240 177 254 104 14 215 215 253 169 85 44 87 240 115 146 150 142 88 160 185 126 116 222 204 59 82 184 101 148 93 22 189 118 67 245 163 166 90 110 11 174 127 52 222 239 114 111 195 123 86 227 61 201 38 221 254 11 60 70 141 137 115 47 27 23 181 26 61 237 48 202 198 53 53 179 58 0 205 27 246 30 198 191 236 77 132 163 218 216 70 172 26 94 3 116 5 123 58 180 5 136 6 187 177 17 163 161 215 198 188 92 55 29 27 251 142 216 233 239 38 195 61 8 44 83 100 120 12 126 196 148 140 67 239 18 81 10 37 210 74 240 105 22 59 28 50 207 224 104 3 60 217 29 36 65 248 78 62 10 233 170 126 156 224 252 186 93 249 58 199 223 0 62 88 76 136 142 109 154 190 15 187 132 85 18 112 28 13 253 173 120 96 15 131 202 23 47 21 125 21 81 235 237 177 149 26 24 207 179 157 48 55 93 65 203 133 36 122 251 137 173 171 181 179 134 217 11 205 139 180 120 154 52 253 6 20 120 14 184 200 129 156 192 0 215 245 157 69 147 255 130 59 216 136 187 29 113 105 96 134 98 64 62 248 228 181 134 76 17 120 209 108 171 127 88 62 94 147 143 184 38 39 117 75 233 134 246 137 136 129 212 86 36 16 191 133 120 169 74 31 118 186 202 84 113 22 33 87 211 105 216 83 233 124 143 110 51 83 149 140 181 236 63 96 94 198 205 204 165 180 168 39 186 186 28 103 227 3 150 178 88 136 173 103 188 178 228 117 147 230 197 136 132 23 29 105 49 27 18 180 17 84 57
        cn: NTAuthCertificates
        objectClass: certificationAuthority
[06/10/2023 04:10:17] CN=NTAuthCertificates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        objectCategory: CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local
        name: NTAuthCertificates
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;LCRPLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        whenCreated: 06/10/2023 04:10:16
        instanceType: 4
        certificateRevocationList: 0
        authorityRevocationList: 0
        cACertificate: 48 130 5 97 48 130 3 73 160 3 2 1 2 2 16 93 212 246 88 235 9 51 159 66 71 65 30 225 249 44 9 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 32 23 13 50 51 48 54 49 48 49 49 48 48 49 52 90 24 15 50 53 50 51 48 54 49 48 49 49 49 48 49 51 90 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 48 130 2 34 48 13 6 9 42 134 72 134 247 13 1 1 1 5 0 3 130 2 15 0 48 130 2 10 2 130 2 1 0 181 2 9 55 210 51 28 20 186 211 235 52 238 4 84 248 182 42 50 116 31 96 48 40 12 19 99 84 133 171 213 133 153 163 41 53 36 45 106 156 8 93 188 90 19 100 251 254 195 48 225 189 49 34 129 242 9 211 68 5 137 71 47 50 101 1 185 109 75 29 1 203 181 63 165 84 206 207 13 168 25 17 107 208 192 220 100 103 46 252 249 248 111 85 182 74 156 139 134 36 28 37 126 213 79 220 37 14 84 120 93 84 175 62 169 100 67 17 138 109 71 252 242 88 120 95 43 193 46 178 23 202 118 102 253 232 254 134 228 99 40 145 66 117 104 78 163 106 160 203 224 80 18 230 138 111 166 189 107 199 199 141 97 95 157 111 28 163 159 1 221 234 112 48 238 27 128 171 15 74 100 56 62 4 187 249 163 99 184 134 108 231 137 26 17 78 248 196 178 161 142 232 251 92 51 244 166 99 251 16 43 132 20 210 197 96 148 145 81 44 44 11 51 38 117 216 160 253 193 55 198 48 202 152 15 146 221 39 174 39 6 90 99 163 194 181 172 19 84 166 34 69 255 40 148 35 99 137 141 133 43 37 184 96 98 83 89 119 245 227 213 160 115 198 92 175 100 73 54 108 145 143 215 22 81 24 170 44 104 60 225 218 174 210 142 148 230 219 38 119 225 194 112 51 8 123 58 212 189 61 73 26 101 25 132 78 33 130 246 228 48 225 104 157 193 42 129 48 216 23 40 77 32 78 88 131 25 165 206 51 5 218 248 118 224 102 211 81 78 180 88 91 247 46 56 173 105 120 106 101 223 92 116 107 201 183 54 192 26 24 100 167 143 182 192 194 32 26 184 22 50 200 81 121 199 48 118 246 82 41 135 58 76 31 195 158 148 66 157 43 177 192 79 198 15 25 74 99 3 191 232 6 207 129 165 168 134 222 217 38 254 158 74 165 168 68 10 247 17 132 56 175 47 143 0 140 162 229 5 63 109 197 57 74 76 166 83 141 222 42 176 240 43 252 46 222 255 8 38 217 212 248 110 240 60 236 175 246 206 27 210 93 33 28 39 18 154 127 90 187 99 41 219 78 132 137 235 103 94 215 119 0 5 145 187 166 88 131 204 255 173 124 148 182 47 28 74 31 181 58 51 131 2 3 1 0 1 163 81 48 79 48 11 6 3 85 29 15 4 4 3 2 1 134 48 15 6 3 85 29 19 1 1 255 4 5 48 3 1 1 255 48 29 6 3 85 29 14 4 22 4 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 30 168 151 68 111 100 174 115 190 33 77 154 53 195 95 110 166 42 36 52 239 27 13 14 49 240 18 143 190 59 136 109 59 68 77 63 173 208 89 131 188 70 68 203 71 235 88 130 21 33 202 66 10 100 59 161 233 70 84 251 183 43 167 237 178 60 184 185 63 36 87 77 105 62 75 135 159 225 74 96 61 49 159 53 198 91 177 75 223 179 21 221 40 181 155 53 146 204 70 251 69 243 53 101 233 111 88 125 145 79 184 227 157 172 123 91 198 197 239 97 21 10 59 155 206 24 246 111 30 69 164 126 201 221 122 191 94 58 90 97 84 123 210 248 136 37 72 147 96 240 177 254 104 14 215 215 253 169 85 44 87 240 115 146 150 142 88 160 185 126 116 222 204 59 82 184 101 148 93 22 189 118 67 245 163 166 90 110 11 174 127 52 222 239 114 111 195 123 86 227 61 201 38 221 254 11 60 70 141 137 115 47 27 23 181 26 61 237 48 202 198 53 53 179 58 0 205 27 246 30 198 191 236 77 132 163 218 216 70 172 26 94 3 116 5 123 58 180 5 136 6 187 177 17 163 161 215 198 188 92 55 29 27 251 142 216 233 239 38 195 61 8 44 83 100 120 12 126 196 148 140 67 239 18 81 10 37 210 74 240 105 22 59 28 50 207 224 104 3 60 217 29 36 65 248 78 62 10 233 170 126 156 224 252 186 93 249 58 199 223 0 62 88 76 136 142 109 154 190 15 187 132 85 18 112 28 13 253 173 120 96 15 131 202 23 47 21 125 21 81 235 237 177 149 26 24 207 179 157 48 55 93 65 203 133 36 122 251 137 173 171 181 179 134 217 11 205 139 180 120 154 52 253 6 20 120 14 184 200 129 156 192 0 215 245 157 69 147 255 130 59 216 136 187 29 113 105 96 134 98 64 62 248 228 181 134 76 17 120 209 108 171 127 88 62 94 147 143 184 38 39 117 75 233 134 246 137 136 129 212 86 36 16 191 133 120 169 74 31 118 186 202 84 113 22 33 87 211 105 216 83 233 124 143 110 51 83 149 140 181 236 63 96 94 198 205 204 165 180 168 39 186 186 28 103 227 3 150 178 88 136 173 103 188 178 228 117 147 230 197 136 132 23 29 105 49 27 18 180 17 84 57
        cn: NTAuthCertificates
        objectClass: certificationAuthority
[06/10/2023 04:10:18] CN=Cert Publishers,CN=Users,DC=dom,DC=local

        member: CN=ADCS,CN=Computers,DC=dom,DC=local
[06/10/2023 04:10:18] CN=Pre-Windows 2000 Compatible Access,CN=Builtin,DC=dom,DC=local

        member: CN=ADCS,CN=Computers,DC=dom,DC=local
[06/10/2023 04:10:18] CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=dom-ADCS-CA,CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=dom-ADCS-CA,CN=AIA,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=dom-ADCS-CA,CN=KRA,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=Deleted Objects,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=Deleted Objects,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=Deleted Objects,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:18] CN=dom-ADCS-CA,CN=Enrollment Services,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;LCRPLORC;;;AU)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(OA;;CR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;AU)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
[06/10/2023 04:10:18] CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213
[06/10/2023 04:10:18] CN=User,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.1
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -1509949440
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 41
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4 1.3.6.1.5.5.7.3.4 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 3
        flags: 66106
        name: User
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: User
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: User
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:18] CN=UserSignature,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.2
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -1509949440
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66082
        name: UserSignature
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: User Signature Only
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: UserSignature
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:18] CN=SmartcardUser,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.3
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -1509949440
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 9
        msPKI-RA-Signature: 0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4 1.3.6.1.5.5.7.3.2 1.3.6.1.4.1.311.20.2.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 11
        flags: 66058
        name: SmartcardUser
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Smartcard User
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: SmartcardUser
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:18] CN=ClientAuth,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.4
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 3
        flags: 66080
        name: ClientAuth
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Authenticated Session
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: ClientAuth
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:18] CN=SmartcardLogon,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.5
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.4.1.311.20.2.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 6
        flags: 66048
        name: SmartcardLogon
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Smartcard Logon
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: SmartcardLogon
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:18] CN=EFS,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.6
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 41
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 3
        flags: 66104
        name: EFS
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Basic EFS
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: EFS
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=Administrator,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.7
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -1509949440
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 41
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.1 1.3.6.1.4.1.311.10.3.4 1.3.6.1.5.5.7.3.4 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66106
        name: Administrator
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Administrator
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: Administrator
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=EFSRecovery,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.8
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 33
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 30 164 232 101 250 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 6
        flags: 66096
        name: EFSRecovery
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: EFS Recovery Agent
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: EFSRecovery
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=CodeSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.9
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.3
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 3
        flags: 66080
        name: CodeSigning
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Code Signing
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CodeSigning
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=CTLSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.10
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 3
        flags: 66080
        name: CTLSigning
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Trust List Signing
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CTLSigning
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=EnrollmentAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.11
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66080
        name: EnrollmentAgent
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Enrollment Agent
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: EnrollmentAgent
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=EnrollmentAgentOffline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.12
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66049
        name: EnrollmentAgentOffline
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Exchange Enrollment Agent (Offline request)
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: EnrollmentAgentOffline
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=MachineEnrollmentAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.13
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 402653184
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 5
        flags: 66144
        name: MachineEnrollmentAgent
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Enrollment Agent (Computer)
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: MachineEnrollmentAgent
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=Machine,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.14
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 402653184
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 5
        flags: 66144
        name: Machine
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Computer
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: Machine
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=DomainController,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.15
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 419430400
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 41
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66156
        name: DomainController
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Domain Controller
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: DomainController
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:19] CN=WebServer,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.16
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft DH SChannel Cryptographic Provider 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66113
        name: WebServer
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Web Server
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: WebServer
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=CA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.17
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 30 164 232 101 250 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.19
        pKIMaxIssuingDepth: -1
        pKIKeyUsage: 134 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 5
        flags: 65745
        name: CA
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Root Certification Authority
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CA
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=SubCA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.18
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 30 164 232 101 250 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.19
        pKIMaxIssuingDepth: -1
        pKIKeyUsage: 134 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 5
        flags: 66257
        name: SubCA
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Subordinate Certification Authority
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: SubCA
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=IPSECIntermediateOnline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.19
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 402653184
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.8.2.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 8
        flags: 66144
        name: IPSECIntermediateOnline
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: IPSec
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: IPSECIntermediateOnline
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=IPSECIntermediateOffline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.20
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.8.2.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 7
        flags: 66113
        name: IPSECIntermediateOffline
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: IPSec (Offline request)
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: IPSECIntermediateOffline
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=OfflineRouter,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.21
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66113
        name: OfflineRouter
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Router (Offline request)
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: OfflineRouter
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=CEPEncryption,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.22
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 4
        flags: 66113
        name: CEPEncryption
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: CEP Encryption
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CEPEncryption
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=ExchangeUser,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.23
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 1
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 7
        flags: 66065
        name: ExchangeUser
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Exchange User
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: ExchangeUser
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=ExchangeUserSignature,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.24
        msPKI-Template-Minor-Revision: 1
        msPKI-Template-Schema-Version: 1
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 0
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 6
        flags: 66049
        name: ExchangeUserSignature
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Exchange Signature Only
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: ExchangeUserSignature
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:20] CN=CrossCA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-RA-Application-Policies: 1.3.6.1.4.1.311.10.3.10
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.25
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 8
        msPKI-RA-Signature: 1
        pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 30 164 232 101 250 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.19
        pKIMaxIssuingDepth: -1
        pKIKeyUsage: 134 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 105
        flags: 67600
        name: CrossCA
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Cross Certification Authority
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CrossCA
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:21] CN=25.1F8C368BD6D0420D481A5B718EE77BEE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.25
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 25.1F8C368BD6D0420D481A5B718EE77BEE
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Cross Certification Authority
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 25.1F8C368BD6D0420D481A5B718EE77BEE
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=25.1F8C368BD6D0420D481A5B718EE77BEE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.25
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 25.1F8C368BD6D0420D481A5B718EE77BEE
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Cross Certification Authority
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 25.1F8C368BD6D0420D481A5B718EE77BEE
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=CAExchange,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.5
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.26
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 1
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.5
        pKIOverlapPeriod: 0 64 150 213 54 255 255 255
        pKIExpirationPeriod: 0 192 27 215 127 250 255 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 106
        flags: 65600
        name: CAExchange
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: CA Exchange
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: CAExchange
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:21] CN=26.4CFA91E4357E6C6BE1DCE16DF3CEF089,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.26
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 26.4CFA91E4357E6C6BE1DCE16DF3CEF089
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: CA Exchange
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 26.4CFA91E4357E6C6BE1DCE16DF3CEF089
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=26.4CFA91E4357E6C6BE1DCE16DF3CEF089,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.26
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 26.4CFA91E4357E6C6BE1DCE16DF3CEF089
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: CA Exchange
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 26.4CFA91E4357E6C6BE1DCE16DF3CEF089
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=KeyRecoveryAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.6
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.27
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: -2113929216
        msPKI-Private-Key-Flag: 16
        msPKI-Enrollment-Flag: 39
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.6
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 128 114 14 93 194 253 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 32 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 105
        flags: 65568
        name: KeyRecoveryAgent
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Key Recovery Agent
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: KeyRecoveryAgent
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:21] CN=27.200A058FE2115C159883F85019910356,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.27
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 27.200A058FE2115C159883F85019910356
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Key Recovery Agent
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 27.200A058FE2115C159883F85019910356
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=27.200A058FE2115C159883F85019910356,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.27
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 27.200A058FE2115C159883F85019910356
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Key Recovery Agent
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 27.200A058FE2115C159883F85019910356
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=DomainControllerAuthentication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1 1.3.6.1.4.1.311.20.2.2
        msPKI-Supersede-Templates: DomainController
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.28
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 134217728
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1 1.3.6.1.4.1.311.20.2.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.17
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 110
        flags: 65632
        name: DomainControllerAuthentication
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Domain Controller Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: DomainControllerAuthentication
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:21] CN=28.E3836BFECFD1A89C0D724350D2A94A74,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.28
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 28.E3836BFECFD1A89C0D724350D2A94A74
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Domain Controller Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 28.E3836BFECFD1A89C0D724350D2A94A74
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:21] CN=28.E3836BFECFD1A89C0D724350D2A94A74,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.28
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 28.E3836BFECFD1A89C0D724350D2A94A74
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Domain Controller Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 28.E3836BFECFD1A89C0D724350D2A94A74
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=DirectoryEmailReplication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.19
        msPKI-Supersede-Templates: DomainController
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.29
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 150994944
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 41
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.19
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.17
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 115
        flags: 65632
        name: DirectoryEmailReplication
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Directory Email Replication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: DirectoryEmailReplication
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:22] CN=29.B1F0B866DF000622DCC6F426C1F3926C,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.29
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 29.B1F0B866DF000622DCC6F426C1F3926C
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Directory Email Replication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 29.B1F0B866DF000622DCC6F426C1F3926C
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=29.B1F0B866DF000622DCC6F426C1F3926C,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.29
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 29.B1F0B866DF000622DCC6F426C1F3926C
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Directory Email Replication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 29.B1F0B866DF000622DCC6F426C1F3926C
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=Workstation,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.30
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 134217728
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 101
        flags: 66144
        name: Workstation
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Workstation Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: Workstation
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:22] CN=30.504A3BD4AEFB2C6073C536EF623B4BDE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.30
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 30.504A3BD4AEFB2C6073C536EF623B4BDE
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Workstation Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 30.504A3BD4AEFB2C6073C536EF623B4BDE
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=30.504A3BD4AEFB2C6073C536EF623B4BDE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.30
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 30.504A3BD4AEFB2C6073C536EF623B4BDE
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Workstation Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 30.504A3BD4AEFB2C6073C536EF623B4BDE
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=RASAndIASServer,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.31
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 1207959552
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 101
        flags: 66144
        name: RASAndIASServer
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;RS)
        showInAdvancedViewOnly: True
        displayName: RAS and IAS Server
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: RASAndIASServer
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:22] CN=31.2CF9667CBC23AE2B9BB3B4E5CBA355B8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.31
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 31.2CF9667CBC23AE2B9BB3B4E5CBA355B8
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: RAS and IAS Server
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 31.2CF9667CBC23AE2B9BB3B4E5CBA355B8
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=31.2CF9667CBC23AE2B9BB3B4E5CBA355B8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.31
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 31.2CF9667CBC23AE2B9BB3B4E5CBA355B8
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: RAS and IAS Server
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 31.2CF9667CBC23AE2B9BB3B4E5CBA355B8
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:22] CN=OCSPResponseSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-RA-Application-Policies: msPKI-Asymmetric-Algorithm`PZPWSTR`RSA`msPKI-Hash-Algorithm`PZPWSTR`SHA1`msPKI-Key-Security-Descriptor`PZPWSTR`D:P(A;;FA;;;BA)(A;;FA;;;SY)(A;;GR;;;S-1-5-80-3804348527-3718992918-2141599610-3686422417-2726379419)`msPKI-Key-Usage`DWORD`2`
        msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.9
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.32
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 3
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 402653184
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 20480
        msPKI-RA-Signature: 0
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.9
        pKIOverlapPeriod: 0 128 44 171 109 254 255 255
        pKIExpirationPeriod: 0 128 55 174 255 244 255 255
        pKICriticalExtensions: 2.5.29.15
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 128 0
        pKIDefaultKeySpec: 2
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 101
        flags: 66112
        name: OCSPResponseSigning
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: OCSP Response Signing
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: OCSPResponseSigning
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:23] CN=32.B07FF99A9402DCF91CCC064FF8CC78A8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.32
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 32.B07FF99A9402DCF91CCC064FF8CC78A8
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: OCSP Response Signing
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 32.B07FF99A9402DCF91CCC064FF8CC78A8
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=32.B07FF99A9402DCF91CCC064FF8CC78A8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.32
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 32.B07FF99A9402DCF91CCC064FF8CC78A8
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: OCSP Response Signing
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 32.B07FF99A9402DCF91CCC064FF8CC78A8
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=KerberosAuthentication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1 1.3.6.1.4.1.311.20.2.2 1.3.6.1.5.2.3.5
        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.33
        msPKI-Template-Minor-Revision: 0
        msPKI-Template-Schema-Version: 2
        msPKI-Minimal-Key-Size: 2048
        msPKI-Certificate-Name-Flag: 138412032
        msPKI-Private-Key-Flag: 0
        msPKI-Enrollment-Flag: 32
        msPKI-RA-Signature: 0
        pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider
        pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2 1.3.6.1.5.5.7.3.1 1.3.6.1.4.1.311.20.2.2 1.3.6.1.5.2.3.5
        pKIOverlapPeriod: 0 128 166 10 255 222 255 255
        pKIExpirationPeriod: 0 64 57 135 46 225 254 255
        pKICriticalExtensions: 2.5.29.15 2.5.29.17
        pKIMaxIssuingDepth: 0
        pKIKeyUsage: 160 0
        pKIDefaultKeySpec: 1
        objectCategory: CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local
        revision: 110
        flags: 65632
        name: KerberosAuthentication
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)
        showInAdvancedViewOnly: True
        displayName: Kerberos Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: KerberosAuthentication
        objectClass: pKICertificateTemplate
[06/10/2023 04:10:23] CN=33.CE9FC3B1F6226A617C80893B32D9B982,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.33
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 33.CE9FC3B1F6226A617C80893B32D9B982
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Kerberos Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 33.CE9FC3B1F6226A617C80893B32D9B982
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=33.CE9FC3B1F6226A617C80893B32D9B982,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.33
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 1
        name: 33.CE9FC3B1F6226A617C80893B32D9B982
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Kerberos Authentication
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 33.CE9FC3B1F6226A617C80893B32D9B982
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=400.17554DB278826990D19BB07FDBC675BF,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.400
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 400.17554DB278826990D19BB07FDBC675BF
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Low Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 400.17554DB278826990D19BB07FDBC675BF
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=400.17554DB278826990D19BB07FDBC675BF,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.400
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 400.17554DB278826990D19BB07FDBC675BF
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Low Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 400.17554DB278826990D19BB07FDBC675BF
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=401.6C5DFE41102365A1651C2B90BB5664C4,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.401
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 401.6C5DFE41102365A1651C2B90BB5664C4
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Medium Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 401.6C5DFE41102365A1651C2B90BB5664C4
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=401.6C5DFE41102365A1651C2B90BB5664C4,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.401
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 401.6C5DFE41102365A1651C2B90BB5664C4
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: Medium Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 401.6C5DFE41102365A1651C2B90BB5664C4
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=402.B8FAF880060003D04A46B1E6F1D72779,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.402
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 402.B8FAF880060003D04A46B1E6F1D72779
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: High Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 402.B8FAF880060003D04A46B1E6F1D72779
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=402.B8FAF880060003D04A46B1E6F1D72779,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.402
        objectCategory: CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local
        flags: 2
        name: 402.B8FAF880060003D04A46B1E6F1D72779
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
        showInAdvancedViewOnly: True
        displayName: High Assurance
        whenCreated: 06/10/2023 04:10:17
        instanceType: 4
        cn: 402.B8FAF880060003D04A46B1E6F1D72779
        objectClass: msPKI-Enterprise-Oid
[06/10/2023 04:10:23] CN=dom-ADCS-CA,CN=Enrollment Services,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        flags: 10
        nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;LCRPLORC;;;AU)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(OA;;CR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;AU)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)
[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:23] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:23] CN=Administrator,CN=Users,DC=dom,DC=local

[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:10:24] CN=dom-ADCS-CA,CN=Enrollment Services,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

[06/10/2023 04:10:24] CN=dom-ADCS-CA,CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        deltaRevocationList: 48 130 3 199 48 130 1 175 2 1 1 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 23 13 50 51 48 54 49 48 49 49 48 48 50 49 90 23 13 50 51 48 54 49 49 50 51 50 48 50 49 90 160 130 1 55 48 130 1 51 48 31 6 3 85 29 35 4 24 48 22 128 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 10 6 3 85 29 20 4 3 2 1 1 48 28 6 9 43 6 1 4 1 130 55 21 4 4 15 23 13 50 51 48 54 49 49 49 49 49 48 50 49 90 48 13 6 3 85 29 27 1 1 255 4 3 2 1 1 48 129 196 6 9 43 6 1 4 1 130 55 21 14 4 129 182 48 129 179 48 129 176 160 129 173 160 129 170 134 129 167 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 100 101 108 116 97 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 11 143 69 236 17 157 115 89 69 111 213 215 181 19 119 26 100 176 44 240 27 187 162 255 250 247 110 232 203 226 226 76 102 57 12 220 205 120 234 186 119 167 75 168 241 214 49 76 220 102 240 29 44 43 54 121 202 85 250 198 28 62 225 216 124 86 77 185 91 43 0 7 127 99 108 165 55 106 122 188 31 15 185 37 198 217 104 138 220 26 23 170 45 113 196 79 34 175 58 190 27 53 1 154 42 23 34 161 215 95 191 88 57 178 114 28 148 95 84 234 224 234 94 191 56 237 79 198 45 59 255 204 73 188 249 172 179 100 208 246 84 14 128 105 65 102 43 9 206 142 252 201 34 29 153 118 54 144 186 240 18 114 172 136 141 49 2 191 206 176 214 125 156 249 4 169 192 134 196 73 17 143 64 12 145 18 176 216 174 142 221 58 1 207 27 70 111 84 92 34 214 131 202 142 109 214 8 157 143 181 195 128 247 56 71 126 125 67 68 241 218 85 147 72 218 131 93 244 8 207 13 187 60 0 23 249 170 186 24 156 226 16 32 118 206 68 186 77 228 91 132 218 43 134 77 142 152 108 193 13 8 4 146 9 222 150 209 97 141 158 110 103 230 203 165 38 143 76 249 32 22 74 120 140 142 224 1 109 80 136 197 163 248 35 33 169 44 244 37 228 20 156 23 202 68 173 133 8 65 243 223 191 70 64 12 143 188 174 232 30 109 19 55 102 168 178 37 163 100 133 17 24 76 69 94 0 20 185 24 215 190 179 5 16 5 175 250 130 12 131 156 165 67 236 1 57 228 125 126 151 112 244 33 30 18 131 253 251 51 190 4 190 244 210 72 157 64 88 24 210 110 148 234 216 94 148 252 35 226 252 248 102 141 100 153 148 97 249 169 64 93 122 86 201 125 150 26 45 233 181 159 249 158 23 9 34 71 26 92 1 127 192 158 127 183 202 39 105 51 64 210 25 247 8 161 4 14 197 34 201 202 98 207 87 82 89 86 178 105 121 117 65 177 217 20 16 104 8 166 40 188 40 49 138 91 208 83 65 255 169 182 146 161 254 16 80 61 58 68 103 73 135 52 129 31 145 75 156 146 102 213 251 119 200 116 246 128 228 242 209 129 17 165 91 242 77 202 165 240 49 143 135
        certificateRevocationList: 48 130 4 127 48 130 2 103 2 1 1 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 23 13 50 51 48 54 49 48 49 49 48 48 50 49 90 23 13 50 51 48 54 49 55 50 51 50 48 50 49 90 160 130 1 239 48 130 1 235 48 31 6 3 85 29 35 4 24 48 22 128 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 10 6 3 85 29 20 4 3 2 1 1 48 28 6 9 43 6 1 4 1 130 55 21 4 4 15 23 13 50 51 48 54 49 55 49 49 49 48 50 49 90 48 129 190 6 3 85 29 46 4 129 182 48 129 179 48 129 176 160 129 173 160 129 170 134 129 167 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 100 101 108 116 97 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 129 202 6 9 43 6 1 4 1 130 55 21 14 4 129 188 48 129 185 48 129 182 160 129 179 160 129 176 134 129 173 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 99 101 114 116 105 102 105 99 97 116 101 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 131 192 42 130 125 17 228 16 150 161 70 5 148 83 231 88 62 44 53 53 50 84 231 107 193 180 191 37 25 82 158 208 249 194 162 80 151 168 245 73 101 235 73 167 120 48 25 135 152 46 43 224 64 59 141 20 185 19 109 11 155 149 44 197 13 55 16 112 13 141 96 243 161 36 4 87 78 125 155 86 192 173 105 203 46 207 102 211 222 179 62 28 35 119 217 67 60 20 189 197 103 86 36 155 0 68 211 49 203 71 171 109 88 128 89 231 47 80 130 36 32 209 226 174 138 193 1 170 118 155 234 76 66 183 90 143 56 109 70 254 200 26 36 73 248 244 51 144 29 235 136 5 185 247 153 167 200 186 135 251 13 84 229 92 177 183 215 180 241 200 96 137 75 150 67 26 71 132 195 6 131 171 215 170 78 0 154 73 59 127 61 23 35 200 165 61 42 11 26 135 6 66 160 103 224 136 144 157 168 90 108 62 75 241 249 41 235 34 24 50 66 26 79 158 173 17 90 4 46 244 174 35 146 73 233 195 208 177 188 223 156 187 50 50 3 46 183 53 98 112 209 91 212 129 63 187 181 8 119 89 111 54 242 84 56 28 8 92 116 147 244 214 179 81 205 135 150 163 191 92 101 176 196 168 251 207 166 36 29 112 36 117 122 118 21 108 235 248 172 224 105 114 135 50 110 20 47 117 132 194 96 116 33 5 29 159 207 150 65 5 13 181 103 94 210 196 111 77 141 39 165 223 172 44 13 5 231 146 137 101 90 148 108 50 150 14 155 95 166 186 49 46 22 31 63 245 57 178 143 64 189 155 72 225 222 135 248 18 115 13 101 119 203 131 99 186 184 210 64 204 10 51 95 194 228 220 160 93 188 153 89 165 2 96 101 235 228 57 234 148 41 128 66 118 73 101 63 17 77 38 147 56 72 183 243 216 148 242 49 209 86 57 219 149 155 91 75 211 149 215 143 195 18 205 186 52 243 212 131 158 234 67 198 36 110 77 190 199 41 194 176 16 115 102 50 178 249 22 248 93 136 99 37 144 51 21 217 43 56 71 94 65 153 19 240 198 223 102 145 113 146 196 194 52 47 56 207 55 221 0 187 203 138 70 165 217 85 152 54 207 10 17 107 78 150 51 55 138 97 73 167 205
[06/10/2023 04:10:24] CN=dom-ADCS-CA,CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

        deltaRevocationList: 48 130 3 199 48 130 1 175 2 1 1 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 23 13 50 51 48 54 49 48 49 49 48 48 50 49 90 23 13 50 51 48 54 49 49 50 51 50 48 50 49 90 160 130 1 55 48 130 1 51 48 31 6 3 85 29 35 4 24 48 22 128 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 10 6 3 85 29 20 4 3 2 1 1 48 28 6 9 43 6 1 4 1 130 55 21 4 4 15 23 13 50 51 48 54 49 49 49 49 49 48 50 49 90 48 13 6 3 85 29 27 1 1 255 4 3 2 1 1 48 129 196 6 9 43 6 1 4 1 130 55 21 14 4 129 182 48 129 179 48 129 176 160 129 173 160 129 170 134 129 167 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 100 101 108 116 97 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 11 143 69 236 17 157 115 89 69 111 213 215 181 19 119 26 100 176 44 240 27 187 162 255 250 247 110 232 203 226 226 76 102 57 12 220 205 120 234 186 119 167 75 168 241 214 49 76 220 102 240 29 44 43 54 121 202 85 250 198 28 62 225 216 124 86 77 185 91 43 0 7 127 99 108 165 55 106 122 188 31 15 185 37 198 217 104 138 220 26 23 170 45 113 196 79 34 175 58 190 27 53 1 154 42 23 34 161 215 95 191 88 57 178 114 28 148 95 84 234 224 234 94 191 56 237 79 198 45 59 255 204 73 188 249 172 179 100 208 246 84 14 128 105 65 102 43 9 206 142 252 201 34 29 153 118 54 144 186 240 18 114 172 136 141 49 2 191 206 176 214 125 156 249 4 169 192 134 196 73 17 143 64 12 145 18 176 216 174 142 221 58 1 207 27 70 111 84 92 34 214 131 202 142 109 214 8 157 143 181 195 128 247 56 71 126 125 67 68 241 218 85 147 72 218 131 93 244 8 207 13 187 60 0 23 249 170 186 24 156 226 16 32 118 206 68 186 77 228 91 132 218 43 134 77 142 152 108 193 13 8 4 146 9 222 150 209 97 141 158 110 103 230 203 165 38 143 76 249 32 22 74 120 140 142 224 1 109 80 136 197 163 248 35 33 169 44 244 37 228 20 156 23 202 68 173 133 8 65 243 223 191 70 64 12 143 188 174 232 30 109 19 55 102 168 178 37 163 100 133 17 24 76 69 94 0 20 185 24 215 190 179 5 16 5 175 250 130 12 131 156 165 67 236 1 57 228 125 126 151 112 244 33 30 18 131 253 251 51 190 4 190 244 210 72 157 64 88 24 210 110 148 234 216 94 148 252 35 226 252 248 102 141 100 153 148 97 249 169 64 93 122 86 201 125 150 26 45 233 181 159 249 158 23 9 34 71 26 92 1 127 192 158 127 183 202 39 105 51 64 210 25 247 8 161 4 14 197 34 201 202 98 207 87 82 89 86 178 105 121 117 65 177 217 20 16 104 8 166 40 188 40 49 138 91 208 83 65 255 169 182 146 161 254 16 80 61 58 68 103 73 135 52 129 31 145 75 156 146 102 213 251 119 200 116 246 128 228 242 209 129 17 165 91 242 77 202 165 240 49 143 135
        certificateRevocationList: 48 130 4 127 48 130 2 103 2 1 1 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 48 66 49 21 48 19 6 10 9 146 38 137 147 242 44 100 1 25 22 5 108 111 99 97 108 49 19 48 17 6 10 9 146 38 137 147 242 44 100 1 25 22 3 100 111 109 49 20 48 18 6 3 85 4 3 19 11 100 111 109 45 65 68 67 83 45 67 65 23 13 50 51 48 54 49 48 49 49 48 48 50 49 90 23 13 50 51 48 54 49 55 50 51 50 48 50 49 90 160 130 1 239 48 130 1 235 48 31 6 3 85 29 35 4 24 48 22 128 20 42 56 232 170 108 175 184 20 1 137 151 83 47 200 211 244 193 20 32 42 48 16 6 9 43 6 1 4 1 130 55 21 1 4 3 2 1 0 48 10 6 3 85 29 20 4 3 2 1 1 48 28 6 9 43 6 1 4 1 130 55 21 4 4 15 23 13 50 51 48 54 49 55 49 49 49 48 50 49 90 48 129 190 6 3 85 29 46 4 129 182 48 129 179 48 129 176 160 129 173 160 129 170 134 129 167 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 100 101 108 116 97 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 129 202 6 9 43 6 1 4 1 130 55 21 14 4 129 188 48 129 185 48 129 182 160 129 179 160 129 176 134 129 173 108 100 97 112 58 47 47 47 67 78 61 100 111 109 45 65 68 67 83 45 67 65 44 67 78 61 65 68 67 83 44 67 78 61 67 68 80 44 67 78 61 80 117 98 108 105 99 37 50 48 75 101 121 37 50 48 83 101 114 118 105 99 101 115 44 67 78 61 83 101 114 118 105 99 101 115 44 67 78 61 67 111 110 102 105 103 117 114 97 116 105 111 110 44 68 67 61 100 111 109 44 68 67 61 108 111 99 97 108 63 99 101 114 116 105 102 105 99 97 116 101 82 101 118 111 99 97 116 105 111 110 76 105 115 116 63 98 97 115 101 63 111 98 106 101 99 116 67 108 97 115 115 61 99 82 76 68 105 115 116 114 105 98 117 116 105 111 110 80 111 105 110 116 48 13 6 9 42 134 72 134 247 13 1 1 13 5 0 3 130 2 1 0 131 192 42 130 125 17 228 16 150 161 70 5 148 83 231 88 62 44 53 53 50 84 231 107 193 180 191 37 25 82 158 208 249 194 162 80 151 168 245 73 101 235 73 167 120 48 25 135 152 46 43 224 64 59 141 20 185 19 109 11 155 149 44 197 13 55 16 112 13 141 96 243 161 36 4 87 78 125 155 86 192 173 105 203 46 207 102 211 222 179 62 28 35 119 217 67 60 20 189 197 103 86 36 155 0 68 211 49 203 71 171 109 88 128 89 231 47 80 130 36 32 209 226 174 138 193 1 170 118 155 234 76 66 183 90 143 56 109 70 254 200 26 36 73 248 244 51 144 29 235 136 5 185 247 153 167 200 186 135 251 13 84 229 92 177 183 215 180 241 200 96 137 75 150 67 26 71 132 195 6 131 171 215 170 78 0 154 73 59 127 61 23 35 200 165 61 42 11 26 135 6 66 160 103 224 136 144 157 168 90 108 62 75 241 249 41 235 34 24 50 66 26 79 158 173 17 90 4 46 244 174 35 146 73 233 195 208 177 188 223 156 187 50 50 3 46 183 53 98 112 209 91 212 129 63 187 181 8 119 89 111 54 242 84 56 28 8 92 116 147 244 214 179 81 205 135 150 163 191 92 101 176 196 168 251 207 166 36 29 112 36 117 122 118 21 108 235 248 172 224 105 114 135 50 110 20 47 117 132 194 96 116 33 5 29 159 207 150 65 5 13 181 103 94 210 196 111 77 141 39 165 223 172 44 13 5 231 146 137 101 90 148 108 50 150 14 155 95 166 186 49 46 22 31 63 245 57 178 143 64 189 155 72 225 222 135 248 18 115 13 101 119 203 131 99 186 184 210 64 204 10 51 95 194 228 220 160 93 188 153 89 165 2 96 101 235 228 57 234 148 41 128 66 118 73 101 63 17 77 38 147 56 72 183 243 216 148 242 49 209 86 57 219 149 155 91 75 211 149 215 143 195 18 205 186 52 243 212 131 158 234 67 198 36 110 77 190 199 41 194 176 16 115 102 50 178 249 22 248 93 136 99 37 144 51 21 217 43 56 71 94 65 153 19 240 198 223 102 145 113 146 196 194 52 47 56 207 55 221 0 187 203 138 70 165 217 85 152 54 207 10 17 107 78 150 51 55 138 97 73 167 205
[06/10/2023 04:11:14] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:13:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:13:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:13:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:13:08] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:13:08] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:13:23] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:17:09] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:17:09] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:17:40] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:18:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:18:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:21:55] CN=ADCS,CN=Computers,DC=dom,DC=local

[06/10/2023 04:23:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[06/10/2023 04:23:04] CN=DC1,OU=Domain Controllers,DC=dom,DC=local

[Summary - DC=dom,DC=local]
Using cookie from file cookie.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

Objects returned: 3

(0) modify CN=Administrator,CN=Users,DC=dom,DC=local

    1> objectGUID: 622cfc56-b836-48ec-b6cc-620db654c5c0

    1> instanceType: 0x4 = ( WRITE )

    1> lastLogonTimestamp: 6/10/2023 4:08:02 AM Pacific Daylight Time

(1) modify CN=Cert Publishers,CN=Users,DC=dom,DC=local

    1> objectGUID: 7732924f-6a2a-491d-b485-dc3570ca11cb

    1> member;range=1-1: <GUID=3a08ca592500494ba421d078cb478ec3>;<SID=010500000000000515000000c0ea6e3ef86a558b2f372ea255040000>;CN=ADCS,CN=Computers,DC=dom,DC=local

(2) modify CN=Pre-Windows 2000 Compatible Access,CN=Builtin,DC=dom,DC=local

    1> objectGUID: 2a9b1298-7293-4481-b42f-6bc5fe9468d7

    1> member;range=1-1: <GUID=3a08ca592500494ba421d078cb478ec3>;<SID=010500000000000515000000c0ea6e3ef86a558b2f372ea255040000>;CN=ADCS,CN=Computers,DC=dom,DC=local

New cookie written to file cookie.bin (108 bytes)



[Summary - CN=Configuration,DC=dom,DC=local]
Using cookie from file cookie-config.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

Objects returned: 54

(0) add CN=dom-ADCS-CA,CN=Certification Authorities,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 5ee6001a-ee6e-4248-9b37-03d4538d9af0

    1> objectGUID: de8ec06d-7e0a-4794-ba2e-7c3f535a913f

    2> objectClass: top; certificationAuthority

    1> cACertificate: <1381 byte blob>

    1> authorityRevocationList:

    1> certificateRevocationList:

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;CA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: dom-ADCS-CA

    1> objectCategory: <GUID=cfafdebd16dd4d4dbe2115f560b01164>;CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local

(1) add CN=NTAuthCertificates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 005f58e3-e289-4bed-93ea-d1be34935007

    1> objectGUID: 9b48ef1b-059e-469b-b9c5-065039bd6220

    2> objectClass: top; certificationAuthority

    1> cACertificate: <1381 byte blob>

    1> authorityRevocationList:

    1> certificateRevocationList:

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: NTAuthCertificates

    1> objectCategory: <GUID=cfafdebd16dd4d4dbe2115f560b01164>;CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local

(2) add CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 9e43d767-b114-4729-af2d-7a3e8999d5e8

    1> objectGUID: 7fd29285-de7a-4f88-bfe3-130b764d3f3a

    2> objectClass: top; container

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;CA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: ADCS

    1> objectCategory: <GUID=f53efe4edee9494681875f47b9334211>;CN=Container,CN=Schema,CN=Configuration,DC=dom,DC=local

(3) add CN=dom-ADCS-CA,CN=AIA,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 2e598cf6-e953-41f1-9ac3-8b596620f753

    1> objectGUID: 98f01871-d6e2-4a57-8dd5-40fd5f0abf05

    2> objectClass: top; certificationAuthority

    1> cACertificate: <1381 byte blob>

    1> authorityRevocationList:

    1> certificateRevocationList:

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: dom-ADCS-CA

    1> objectCategory: <GUID=cfafdebd16dd4d4dbe2115f560b01164>;CN=Certification-Authority,CN=Schema,CN=Configuration,DC=dom,DC=local

(4) add CN=dom-ADCS-CA,CN=KRA,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: d829b984-3caf-4762-a304-1affe81a38c6

    1> objectGUID: 5434bb7a-b470-4b4a-910c-c97dd24e790e

    2> objectClass: top; msPKI-PrivateKeyRecoveryAgent

    1> userCertificate:

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: dom-ADCS-CA

    1> objectCategory: <GUID=3c51ce8f67c6b040b368d858e92bdf5e>;CN=ms-PKI-Private-Key-Recovery-Agent,CN=Schema,CN=Configuration,DC=dom,DC=local

(5) modify CN=Deleted Objects,CN=Configuration,DC=dom,DC=local

    1> objectGUID: 8bbf61fd-fa4f-44c1-8c95-d2f1b8c6fe3d

    1> instanceType: 0x4 = ( WRITE )

    1> nTSecurityDescriptor: O:SYG:SYD:PAI(A;;LC;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;;LCRP;;;BA)(A;;KA;;;SY)

(6) modify CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> objectGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> instanceType: 0x4 = ( WRITE )

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213

(7) add CN=User,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: d3ac68bd-b91f-49aa-a993-b27d4bfbf9f4

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: User

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: User

    1> flags: 66106

    1> revision: 3

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    3> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4; 1.3.6.1.5.5.7.3.4; 1.3.6.1.5.5.7.3.2

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 41

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: -1509949440

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.1

(8) add CN=UserSignature,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 32bbb955-670b-4501-a40c-5e5bcb608456

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: User Signature Only

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: UserSignature

    1> flags: 66082

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    2> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4; 1.3.6.1.5.5.7.3.2

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -1509949440

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.2

(9) add CN=SmartcardUser,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: bd3132cf-f881-425a-9745-09deaa3cd72b

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Smartcard User

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: SmartcardUser

    1> flags: 66058

    1> revision: 11

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    3> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4; 1.3.6.1.5.5.7.3.2; 1.3.6.1.4.1.311.20.2.2

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 9

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -1509949440

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.3

(10) add CN=ClientAuth,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 2f274ba2-f499-48b2-a7ac-afb8d5d8a014

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Authenticated Session

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: ClientAuth

    1> flags: 66080

    1> revision: 3

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.4

(11) add CN=SmartcardLogon,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 8bef8e2b-f06e-45fb-ba66-8d08104ac815

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Smartcard Logon

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: SmartcardLogon

    1> flags: 66048

    1> revision: 6

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    2> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.4.1.311.20.2.2

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.5

(12) add CN=EFS,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: ceb86963-32a7-4ba8-b7e6-887f2df7807b

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Basic EFS

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DU)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: EFS

    1> flags: 66104

    1> revision: 3

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 41

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.6

(13) add CN=Administrator,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 1bc899f8-59c6-4145-83fa-7b5d2f695a0f

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Administrator

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: Administrator

    1> flags: 66106

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    4> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.1; 1.3.6.1.4.1.311.10.3.4; 1.3.6.1.5.5.7.3.4; 1.3.6.1.5.5.7.3.2

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 41

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: -1509949440

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.7

(14) add CN=EFSRecovery,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 39729d5a-2e70-40ff-a790-558e7aba18ce

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: EFS Recovery Agent

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: EFSRecovery

    1> flags: 66096

    1> revision: 6

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.4.1

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 33

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.8

(15) add CN=CodeSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 8bb4ed00-8e98-4132-a845-af6f07457af0

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Code Signing

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CodeSigning

    1> flags: 66080

    1> revision: 3

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.3

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.9

(16) add CN=CTLSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: e4ba5eae-9173-436b-a460-f018274c975b

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Trust List Signing

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CTLSigning

    1> flags: 66080

    1> revision: 3

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.10.3.1

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.10

(17) add CN=EnrollmentAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 1be69b9e-1abe-4897-b36b-97f9271988f9

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Enrollment Agent

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: EnrollmentAgent

    1> flags: 66080

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.11

(18) add CN=EnrollmentAgentOffline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 9e52ea86-75d4-46f6-b056-2d4cb3ac909c

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Exchange Enrollment Agent (Offline request)

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: EnrollmentAgentOffline

    1> flags: 66049

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.12

(19) add CN=MachineEnrollmentAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 50fa4f83-f72a-4207-a82f-909feb382cb1

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Enrollment Agent (Computer)

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: MachineEnrollmentAgent

    1> flags: 66144

    1> revision: 5

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 402653184

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.13

(20) add CN=Machine,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: d0e24107-e2c9-4366-b057-a973bf8469f7

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Computer

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: Machine

    1> flags: 66144

    1> revision: 5

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    2> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 402653184

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.14

(21) add CN=DomainController,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: a3f76c34-fb96-42e6-a9a6-9bd835b3da13

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Domain Controller

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: DomainController

    1> flags: 66156

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    2> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 41

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 419430400

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.15

(22) add CN=WebServer,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 3e4a71d0-9c62-473a-a319-ea46a079f8bf

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Web Server

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: WebServer

    1> flags: 66113

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.1

    2> pKIDefaultCSPs: 2,Microsoft DH SChannel Cryptographic Provider; 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.16

(23) add CN=CA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: d7cb7d3f-b311-4e1b-b10e-0ee30bf09759

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Root Certification Authority

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CA

    1> flags: 65745

    1> revision: 5

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: -1

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.19

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.17

(24) add CN=SubCA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 6ca85c3c-d942-4fc6-8041-7080dec7b393

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Subordinate Certification Authority

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: SubCA

    1> flags: 66257

    1> revision: 5

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: -1

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.19

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.18

(25) add CN=IPSECIntermediateOnline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 3fc43846-7ba6-42da-a7aa-e9a8292048a5

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: IPSec

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: IPSECIntermediateOnline

    1> flags: 66144

    1> revision: 8

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.8.2.2

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 402653184

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.19

(26) add CN=IPSECIntermediateOffline,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 700c1b72-c3e6-4f2f-8894-ab5bf05c2213

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: IPSec (Offline request)

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: IPSECIntermediateOffline

    1> flags: 66113

    1> revision: 7

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.8.2.2

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.20

(27) add CN=OfflineRouter,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 526a2219-af39-4f75-8f16-41d170c4a207

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Router (Offline request)

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: OfflineRouter

    1> flags: 66113

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.21

(28) add CN=CEPEncryption,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 295006ce-c501-4d5b-a500-0ca62fa50bc4

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: CEP Encryption

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CEPEncryption

    1> flags: 66113

    1> revision: 4

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.20.2.1

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.22

(29) add CN=ExchangeUser,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 0db0b2fd-d72c-4d41-8d03-611215d53bda

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Exchange User

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: ExchangeUser

    1> flags: 66065

    1> revision: 7

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 1

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.23

(30) add CN=ExchangeUserSignature,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 567538f6-3c76-4bf3-9e3f-5b9eac95ca3e

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Exchange Signature Only

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: ExchangeUserSignature

    1> flags: 66049

    1> revision: 6

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.4

    3> pKIDefaultCSPs: 3,Microsoft Base DSS Cryptographic Provider; 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 0

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 1

    1> msPKI-Template-Minor-Revision: 1

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.24

(31) add CN=CrossCA,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 38e49d92-d4a9-4188-aaee-e311224fcd0d

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Cross Certification Authority

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CrossCA

    1> flags: 67600

    1> revision: 105

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: -1

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.19

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 1

    1> msPKI-Enrollment-Flag: 8

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.25

    1> msPKI-RA-Application-Policies: 1.3.6.1.4.1.311.10.3.10

(32) add CN=25.1F8C368BD6D0420D481A5B718EE77BEE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 4ec50267-e7e0-4a19-a02f-fc8467277c34

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Cross Certification Authority

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 25.1F8C368BD6D0420D481A5B718EE77BEE

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.25

(33) add CN=CAExchange,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: c12eb2e4-b09e-4c2a-90c3-9af9919b5d03

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: CA Exchange

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: CAExchange

    1> flags: 65600

    1> revision: 106

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.5

    2> pKIDefaultCSPs: 2,Microsoft Base Cryptographic Provider v1.0; 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 1

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.26

    1> msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.5

(34) add CN=26.4CFA91E4357E6C6BE1DCE16DF3CEF089,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 0bc2c580-69d5-4635-ab3d-e2922af0bd45

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: CA Exchange

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 26.4CFA91E4357E6C6BE1DCE16DF3CEF089

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.26

(35) add CN=KeyRecoveryAgent,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: cac4893a-af9e-46ad-be85-cfda55d50e0b

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Key Recovery Agent

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: KeyRecoveryAgent

    1> flags: 65568

    1> revision: 105

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.6

    1> pKIDefaultCSPs: 1,Microsoft Enhanced Cryptographic Provider v1.0

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 39

    1> msPKI-Private-Key-Flag: 16

    1> msPKI-Certificate-Name-Flag: -2113929216

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.27

    1> msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.6

(36) add CN=27.200A058FE2115C159883F85019910356,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 32932219-418c-4624-aab3-c21cb1c4d370

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Key Recovery Agent

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 27.200A058FE2115C159883F85019910356

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.27

(37) add CN=DomainControllerAuthentication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 286c1e63-6861-4946-a2d0-c58d64da7d5e

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Domain Controller Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: DomainControllerAuthentication

    1> flags: 65632

    1> revision: 110

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.17

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    3> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1; 1.3.6.1.4.1.311.20.2.2

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 134217728

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.28

    1> msPKI-Supersede-Templates: DomainController

    3> msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1; 1.3.6.1.4.1.311.20.2.2

(38) add CN=28.E3836BFECFD1A89C0D724350D2A94A74,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: b4195686-4cd8-4300-8929-a6b2c25ddfc9

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Domain Controller Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 28.E3836BFECFD1A89C0D724350D2A94A74

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.28

(39) add CN=DirectoryEmailReplication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 0f09a673-e0b6-4f12-86b1-71e667e67794

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Directory Email Replication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: DirectoryEmailReplication

    1> flags: 65632

    1> revision: 115

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.17

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.4.1.311.21.19

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 41

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 150994944

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.29

    1> msPKI-Supersede-Templates: DomainController

    1> msPKI-Certificate-Application-Policy: 1.3.6.1.4.1.311.21.19

(40) add CN=29.B1F0B866DF000622DCC6F426C1F3926C,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: dd855689-f1a9-4162-9b14-df3a5d7b3586

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Directory Email Replication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 29.B1F0B866DF000622DCC6F426C1F3926C

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.29

(41) add CN=Workstation,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 5d9018cd-e713-4990-a3a5-2da0968a5012

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Workstation Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DC)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: Workstation

    1> flags: 66144

    1> revision: 101

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 134217728

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.30

    1> msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2

(42) add CN=30.504A3BD4AEFB2C6073C536EF623B4BDE,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 5c95eaeb-9f3a-485c-b27e-46b5439523e0

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Workstation Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 30.504A3BD4AEFB2C6073C536EF623B4BDE

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.30

(43) add CN=RASAndIASServer,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: f9e7d3a2-caa9-451a-be69-81446d0560be

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: RAS and IAS Server

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;RS)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: RASAndIASServer

    1> flags: 66144

    1> revision: 101

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    2> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 1207959552

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.31

    2> msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1

(44) add CN=31.2CF9667CBC23AE2B9BB3B4E5CBA355B8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 14fcdd72-aaa2-4c0d-9e67-0e014ea717a0

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: RAS and IAS Server

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 31.2CF9667CBC23AE2B9BB3B4E5CBA355B8

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.31

(45) add CN=OCSPResponseSigning,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: a2f0a4ad-e1bd-48eb-b2b0-b71b36f43777

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: OCSP Response Signing

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: OCSPResponseSigning

    1> flags: 66112

    1> revision: 101

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 2

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    1> pKICriticalExtensions: 2.5.29.15

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    1> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.9

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 20480

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 402653184

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 3

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.32

    1> msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.9

    1> msPKI-RA-Application-Policies: msPKI-Asymmetric-Algorithm`PZPWSTR`RSA`msPKI-Hash-Algorithm`PZPWSTR`SHA1`msPKI-Key-Security-Descriptor`PZPWSTR`D:P(A;;FA;;;BA)(A;;FA;;;SY)(A;;GR;;;S-1-5-80-3804348527-3718992918-2141599610-3686422417-2726379419)`msPKI-Key-Usage`DWORD`2`

(46) add CN=32.B07FF99A9402DCF91CCC064FF8CC78A8,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: b8f73640-c7b4-4a91-a4b8-ef30724a1ecd

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: OCSP Response Signing

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 32.B07FF99A9402DCF91CCC064FF8CC78A8

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.32

(47) add CN=KerberosAuthentication,CN=Certificate Templates,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: ff0c99c0-b708-4ef2-a701-68b9b4bccc7a

    1> objectGUID: 2d42b816-8c2c-4567-a812-55d7afb0e0fd

    2> objectClass: top; pKICertificateTemplate

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Kerberos Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:PAI(OA;;RPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;S-1-5-21-1047456448-2337630968-2720937775-498)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DA)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;S-1-5-21-1047456448-2337630968-2720937775-519)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;DD)(OA;;RPWPCR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;ED)(OA;;RPWPCR;a05b8cc2-17bc-4802-a710-e7c15ab866a2;;ED)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;DA)(A;;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;;LCRPLORC;;;AU)

    1> name: KerberosAuthentication

    1> flags: 65632

    1> revision: 110

    1> objectCategory: <GUID=f49b97a9a21f3444a3375cd7c1fc6f3a>;CN=PKI-Certificate-Template,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> pKIDefaultKeySpec: 1

    1> pKIKeyUsage:

    1> pKIMaxIssuingDepth: 0

    2> pKICriticalExtensions: 2.5.29.15; 2.5.29.17

    1> pKIExpirationPeriod: <8 byte blob>

    1> pKIOverlapPeriod: <8 byte blob>

    4> pKIExtendedKeyUsage: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1; 1.3.6.1.4.1.311.20.2.2; 1.3.6.1.5.2.3.5

    1> pKIDefaultCSPs: 1,Microsoft RSA SChannel Cryptographic Provider

    1> msPKI-RA-Signature: 0

    1> msPKI-Enrollment-Flag: 32

    1> msPKI-Private-Key-Flag: 0

    1> msPKI-Certificate-Name-Flag: 138412032

    1> msPKI-Minimal-Key-Size: 2048

    1> msPKI-Template-Schema-Version: 2

    1> msPKI-Template-Minor-Revision: 0

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.33

    4> msPKI-Certificate-Application-Policy: 1.3.6.1.5.5.7.3.2; 1.3.6.1.5.5.7.3.1; 1.3.6.1.4.1.311.20.2.2; 1.3.6.1.5.2.3.5

(48) add CN=33.CE9FC3B1F6226A617C80893B32D9B982,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: bd75a1db-60e7-4fd1-b139-25bf5bcd7a92

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Kerberos Authentication

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 33.CE9FC3B1F6226A617C80893B32D9B982

    1> flags: 1

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.33

(49) add CN=400.17554DB278826990D19BB07FDBC675BF,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 6de140df-0e11-4984-b8e4-400fdbab682f

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Low Assurance

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 400.17554DB278826990D19BB07FDBC675BF

    1> flags: 2

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.400

(50) add CN=401.6C5DFE41102365A1651C2B90BB5664C4,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 05255757-07a5-4517-94f7-e8ba179bef27

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: Medium Assurance

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 401.6C5DFE41102365A1651C2B90BB5664C4

    1> flags: 2

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.401

(51) add CN=402.B8FAF880060003D04A46B1E6F1D72779,CN=OID,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7a36f8d5-3de4-4c3f-bfa8-7c16e7c9c7d5

    1> objectGUID: 20c6acee-7d42-41d8-9fdf-e141fdcde82d

    2> objectClass: top; msPKI-Enterprise-Oid

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:17 AM Pacific Daylight Time

    1> displayName: High Assurance

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;;LCRPLORC;;;AU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SY)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: 402.B8FAF880060003D04A46B1E6F1D72779

    1> flags: 2

    1> objectCategory: <GUID=9083a2a9b5436d4381968d9dedec6637>;CN=ms-PKI-Enterprise-Oid,CN=Schema,CN=Configuration,DC=dom,DC=local

    1> msPKI-Cert-Template-OID: 1.3.6.1.4.1.311.21.8.14022710.8053821.4148415.11041814.15190471.213.1.402

(52) add CN=dom-ADCS-CA,CN=Enrollment Services,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 242b4214-5c08-4956-8fa6-c60e9eb14356

    1> objectGUID: ff4c809a-f78a-4c18-b423-877aa13cdca8

    2> objectClass: top; pKIEnrollmentService

    1> cACertificate: <1381 byte blob>

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> displayName: dom-ADCS-CA

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(OA;;CR;0e10c968-78fb-11d2-90d4-00c04f79dc55;;AU)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;OICI;LCRPLORC;;;AU)(A;CIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;CIID;CCLCSWRPWPLOCRSDRCWDWO;;;DA)

    1> name: dom-ADCS-CA

    1> flags: 10

    1> dNSHostName: ADCS.dom.local

    1> cACertificateDN: CN=dom-ADCS-CA, DC=dom, DC=local

    1> objectCategory: <GUID=5454bf056798ca4fb567467f53c49932>;CN=PKI-Enrollment-Service,CN=Schema,CN=Configuration,DC=dom,DC=local

    11> certificateTemplates: DirectoryEmailReplication; DomainControllerAuthentication; KerberosAuthentication; EFSRecovery; EFS; DomainController; WebServer; Machine; User; SubCA; Administrator

(53) add CN=dom-ADCS-CA,CN=ADCS,CN=CDP,CN=Public Key Services,CN=Services,CN=Configuration,DC=dom,DC=local

    1> parentGUID: 7fd29285-de7a-4f88-bfe3-130b764d3f3a

    1> objectGUID: ae9be388-b90b-4371-bd7a-80478b483409

    2> objectClass: top; cRLDistributionPoint

    1> certificateRevocationList: <1155 byte blob>

    1> deltaRevocationList: <971 byte blob>

    1> instanceType: 0x4 = ( WRITE )

    1> whenCreated: 6/10/2023 4:10:16 AM Pacific Daylight Time

    1> showInAdvancedViewOnly: TRUE

    1> nTSecurityDescriptor: O:S-1-5-21-1047456448-2337630968-2720937775-519G:S-1-5-21-1047456448-2337630968-2720937775-519D:AI(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-1109)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICI;LCRPLORC;;;WD)(A;OICIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;DA)(A;OICIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;CA)(A;OICIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;S-1-5-21-1047456448-2337630968-2720937775-519)(A;OICIID;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;OICIID;LCRPLORC;;;WD)

    1> name: dom-ADCS-CA

    1> objectCategory: <GUID=3fd988af833137449d20e40782f9fc99>;CN=CRL-Distribution-Point,CN=Schema,CN=Configuration,DC=dom,DC=local

New cookie written to file cookie-config.bin (108 bytes)



[Summary - CN=Schema,CN=Configuration,DC=dom,DC=local]
Using cookie from file cookie-schema.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

No Changes

New cookie written to file cookie-schema.bin (108 bytes)



[Summary - DC=ForestDnsZones,DC=dom,DC=local]
Using cookie from file cookie-forestdns.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

No Changes

New cookie written to file cookie-forestdns.bin (108 bytes)



[Summary - DC=DomainDnsZones,DC=dom,DC=local]
Using cookie from file cookie-domaindns.bin (108 bytes)

==== SOURCE DSA: DC1.DOM.LOCAL ====

Objects returned: 1

(0) modify DC=dc1,DC=dom.local,CN=MicrosoftDNS,DC=DomainDnsZones,DC=dom,DC=local

    1> objectGUID: 56d316eb-4a58-4af0-8d55-c8823a1be2ef

    1> instanceType: 0x4 = ( WRITE )

    2> dnsRecord: <28 byte blob>; <28 byte blob>

New cookie written to file cookie-domaindns.bin (108 bytes)



PS C:\Users\Administrator\Desktop>