# Corporate IT & Security

GageMate is distributed as a packaged Windows desktop application. Corporate security controls may restrict downloads, installation, or execution.

## IT review checklist

- Confirm the publisher and official release source.
- Review the EULA and third-party notices included with the installer.
- Validate the published SHA-256 checksum, if provided.
- Determine whether the installer is code-signed and inspect any signature.
- Evaluate application control policies (AppLocker / WDAC) and endpoint detection tools.
- Confirm whether administrator elevation is required.
- Validate data storage, temporary files, telemetry, network traffic, and update behavior for the actual release.
- Test deployment on a representative managed Windows workstation.

!!! danger "Do not weaken security controls"
    Do not turn off Microsoft Defender, SmartScreen, endpoint detection, or application allowlisting just to install GageMate. Obtain IT approval and use the organization's authorized software review process.

## Information to publish after validation

**Publisher:** ArcPath Automation & Design LLC  
**Application:** GageMate  
**Release:** 1.3.0  
**Installer filename:** To be verified  
**SHA-256:** To be published  
**Code-signing status:** To be verified  
**Network and telemetry behavior:** To be verified  
**Local data locations:** To be verified
