# Hi there, we're AdminSignal 👋

[![Website](https://img.shields.io/badge/Website-adminsignal.com-0078D4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://adminsignal.com)
[![Focus](https://img.shields.io/badge/Focus-Intune%20%7C%20ConfigMgr%20%7C%20Windows%2011-23272A?style=for-the-badge&logo=windows&logoColor=white)](https://adminsignal.com)
[![GitHub](https://img.shields.io/badge/Scripts-PowerShell%20%7C%20KQL-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/AdminSignalHQ)

**AdminSignal** ([adminsignal.com](https://adminsignal.com)) is an engineering resource for IT administrators, systems engineers, and endpoint mobility professionals navigating the shift from legacy infrastructure to modern cloud management.

We focus on practical, battle-tested solutions for enterprise Windows environments—demystifying policy precedence, co-management transitions, Windows Autopilot provisioning, and automated endpoint remediations.

---

### 🚀 Flagship Toolkits & Repositories

| Repository | Description | Included Tools |
| :--- | :--- | :--- |
| 🛡️ [**`intune-remediations`**](https://github.com/AdminSignalHQ/intune-remediations) | Production-ready Proactive Remediation script packages (`Detect` + `Remediate`) for Microsoft Intune. | GPO tattoo cleanup, WUfB client repair, BitLocker Entra ID escrow, stale profile cleanup, NTP time sync, DO cache reset. |
| ⚖️ [**`gpo-intune-auditor`**](https://github.com/AdminSignalHQ/gpo-intune-auditor) | Client-side PowerShell diagnostic toolkit for hybrid Windows endpoints. | `Get-AdminSignalPolicyAudit.ps1`, `Get-CoManagementSliders.ps1`, `Export-TattooedGPOReport.ps1`. |
| 🚀 [**`autopilot-diagnostics-toolkit`**](https://github.com/AdminSignalHQ/autopilot-diagnostics-toolkit) | Pre-flight readiness, OOBE ESP status inspector, and automated diagnostic log bundler for Windows Autopilot. | `Test-AutopilotReadiness.ps1`, `Get-AutopilotESPStatus.ps1`, `Export-AutopilotDiagnosticBundle.ps1`. |
| 📦 [**`win32-packaging-templates`**](https://github.com/AdminSignalHQ/win32-packaging-templates) | Standardized zero-dependency PowerShell wrappers, version-safe detection scripts, and requirement rules for `.intunewin` apps. | `Invoke-AppDeployWrapper.ps1`, `Detect-RegistryAppVersion.ps1`, `Detect-FileAndServiceHealth.ps1`, `Test-DeviceReadinessRequirement.ps1`. |
| 🔍 [**`endpoint-kql-queries`**](https://github.com/AdminSignalHQ/endpoint-kql-queries) | Operational KQL hunting and posture queries for Microsoft Defender XDR tailored to endpoint engineers. | ASR rule audit summarizer, vulnerable kernel driver detector, TVM critical patch gaps, Tamper Protection & local admin tracking. |

---

### 📖 Featured Deep Dives on [adminsignal.com](https://adminsignal.com)

* **GPO vs. Intune Precedence**: What happens when Group Policy and Intune target the exact same setting, and how `MDMWinsOverGP` behaves in practice.
* **Co-Management Workload Shifting**: Transitioning from SCCM/ConfigMgr to Intune for Windows Update for Business and Endpoint Protection without disrupting end users.
* **Retiring Task Sequence OSD**: Practical blueprints for adopting Windows Autopilot with minimal downtime and automated app provisioning.
* **Feature Update Servicing & Ring Management**: Validating readiness, driver compatibility, and rollback safeguards across pilot and production rings.

---

### 💬 Community & Feedback

Have a suggestion for a remediation script, or ran into an undocumented CSP behavior in the latest Windows 11 build?
* Open an issue on any repository above
* Read our full technical guides at [**adminsignal.com**](https://adminsignal.com)
