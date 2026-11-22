# Technical Service Case: Storage Upgrade & OS Installation on Apple MacBook Pro A1466

## 1. Context & Problem Statement
- **Target System:** Apple MacBook Pro A1466.
- **Initial Storage:** Factory-installed Samsung 128 GB M.2 SSD (`MZ-JPV128S`) with a proprietary 12+16-pin (28-pin total) PCIe connector.
- **Operational Issue:** Limited internal storage capacity on the original 128 GB drive, requiring an upgrade to higher storage capacity and a compatible macOS installation while preserving the client's original files.

## 2. Compatibility Assessment & Hardware Selection
- **Model & Year Compatibility:** Researched and validated hardware and OS compatibility specifically for the MacBook Pro A1466 model and production year.
- **Interface & Adapter Requirement:** Because the factory Samsung `MZ-JPV128S` (128 GB) uses a proprietary 12+16-pin (28-pin) PCIe interface, a dedicated 28-pin compatible adapter was sourced and tested to accept an M.2 2280 PCIe NVMe SSD.
- **PCIe Generation & Thermal Constraints:**
  - Evaluated multiple SSD options across compatibility tests.
  - **PCIe Gen4 SSDs** were excluded due to incompatibility in this setup.
  - Selected a **PCIe Gen3** drive—**Western Digital WD Blue SN550 1 TB (`WDS100T2B0C`)**, M.2 2280 PCIe Gen3 x4 NVMe—accounting for read/write performance characteristics and thermal behavior to mitigate overheating risk.
- **Operating System Compatibility:** Confirmed compatibility for **macOS Monterey 12.7.6** on the target model/year prior to installation.

## 3. Implementation & Data Preservation
1. **Internal Storage Upgrade:** Installed the **Western Digital WD Blue SN550 1 TB (`WDS100T2B0C`)** M.2 2280 PCIe Gen3 x4 NVMe SSD using the compatible 12+16-pin (28-pin) adapter.
2. **Operating System Setup:** Installed **macOS Monterey 12.7.6** after verifying model and OS compatibility.
3. **Original Drive Conversion & Backup Retention:** Converted the factory **Samsung `MZ-JPV128S` (128 GB)** SSD into an external SSD using a Mac SSD-to-USB 3.2 enclosure so the client's original files remain preserved and accessible as a backup.

## 4. Validation & Evidence
- Verified system boot, internal drive detection/capacity, **macOS Monterey 12.7.6** operation, and external USB 3.2 enclosure access to the client's original files.
- **Visual Evidence:** Store sanitized photos in `01-it-support/evidence/` and link them below after verifying no private client data, credentials, or sensitive identifiers are visible:
  - `![Original 128GB Samsung MZ-JPV128S 28-pin SSD](evidence/<20251203_174128>.jpg)`
  - `![28-pin Adapter and WD Blue SN550 1TB WDS100T2B0C](evidence/<20251203_172626>.jpg)`
  - `![USB 3.2 External Enclosure Setup](evidence/<20251203_195318>.jpg)`

## 5. Security & Privacy Note
- No personal client data, account credentials, or confidential files are included in this documentation or its accompanying images.
