# EFI Clover 5163 - Aorus Z790 Elite AX + RX 6900 XT

## 📋 Especificações do Hardware

### 🖥️ **Placa Mãe**
- **Modelo**: Gigabyte Aorus Z790 Elite AX (rev. 1.0)
- **Chipset**: Intel Z790
- **Socket**: LGA 1700
- **Suporte CPU**: Intel Core 13ª e 12ª geração
- **Memória**: DDR5 Dual Channel (4 slots DIMM)
- **WiFi**: Wi-Fi 6E 802.11ax 2T2R
- **Bluetooth**: 5.0
- **LAN**: 2.5GbE Ethernet
- **Slots PCIe**: 1x PCIe 5.0 x16 + 2x PCIe adicionais
- **Armazenamento**: 4x M.2 PCIe 4.0 + 6x SATA 6Gb/s
- **USB Traseiro**: 1x USB 3.2 Gen 2x2 Type-C + 2x USB 3.2 Gen 2 Type-A + 3x USB 3.2 Gen 1
- **Áudio**: Capacitores de alta qualidade + WIMA audiófilo
- **Recursos**: M.2 EZ-Latch Plus, Multi-Key, Smart Fan 6, RGB FUSION 2.0
- **BIOS**: F13 (9.57MB) - 2025/06/19 (Última versão)

### 🔧 **Processador**
- **Modelo**: Intel Core i9-13900K (Raptor Lake)
- **Arquitetura**: 13th Gen Intel Core
- **Cores**: 24 (8P + 16E)
- **Threads**: 32

### 🎮 **Placa de Vídeo**
- **Modelo**: AMD Radeon RX 6900 XT
- **Fabricante**: Aorus (Gigabyte)
- **Arquitetura**: RDNA 2
- **VRAM**: 16GB GDDR6

### 📡 **WiFi/Bluetooth**
- **Modelo**: Broadcom BCM94360 PCIe
- **Padrão**: WiFi 6 + Bluetooth 5.0

### 💾 **Armazenamento**
- **Tipo**: NVMe SSD
- **Interface**: PCIe 4.0

## 🚀 **Compatibilidade macOS**

### ✅ **Versões Suportadas**
- **macOS Sequoia** (15.x)
- **macOS Sonoma** (14.x)
- **macOS Ventura** (13.x)

### 🔧 **Funcionalidades Testadas**
- ✅ Boot completo
- ✅ Aceleração de hardware (Metal)
- ✅ WiFi e Bluetooth
- ✅ Áudio (AppleALC)
- ✅ USB (mapeado)
- ✅ Sleep/Wake
- ✅ Power Management

## 📦 **Kexts Incluídos**

### 🎯 **Essenciais**
- **Lilu.kext** - Framework base
- **AppleALC.kext** - Áudio
- **NootRX.kext** - Suporte AMD RX 6900 XT
- **LucyRTL8125Ethernet.kext** - Ethernet
- **itlwm.kext** - WiFi Intel (se aplicável)

### 🔧 **Utilitários**
- **FakeSMC.kext** - Monitoramento de hardware
- **ACPIMonitor.kext** - Monitoramento ACPI
- **IntelCPUMonitor.kext** - Monitoramento CPU
- **RadeonMonitor.kext** - Monitoramento GPU AMD
- **ITEIT87x.kext** - Sensores de temperatura

### 🛠️ **Correções**
- **USBMap.kext** - Mapeamento USB
- **USBWakeFixup.kext** - Correção wake USB
- **HibernationFixup.kext** - Correção hibernação
- **NVMeFix.kext** - Correção NVMe
- **RTCMemoryFixup.kext** - Correção RTC
- **RestrictEvents.kext** - Restrições de eventos

## ⚙️ **ACPI Patches**

### 📄 **SSDTs Incluídos**
- **SSDT-ALC-Raptor.aml** - Áudio para Raptor Lake
- **SSDT-EC.aml** - Embedded Controller
- **SSDT-PLUG.aml** - Power Management
- **SSDT-PMC.aml** - Power Management Controller
- **SSDT-USBX.aml** - USB Power Management
- **SSDT-USBW.aml** - USB Wake
- **SSDT-USBTAHOE2.aml** - USB Tahoe
- **SSDT-UIAC.aml** - USB Interface Association
- **SSDT-HPET.aml** - High Precision Event Timer
- **SSDT-RTCAWAC.aml** - RTC AWAC
- **SSDT-SBUS-MCHC.aml** - System Bus
- **SSDT-Sbus-PC00.aml** - System Bus PC00
- **SSDT-GPRW.aml** - General Purpose Register Wake
- **SSDT-PRW.aml** - Power Resource Wake
- **SSDT-BRG0.aml** - Bridge 0
- **SSDT-xh_rps14.aml** - XHCI RPS14
- **DMAR.aml** - DMA Remapping

## 🎨 **Temas Incluídos**
- **Atomic** - Tema moderno com animações
- **DarkBootX** - Tema escuro minimalista

## 📋 **Requisitos do Sistema**

### 💻 **Hardware Mínimo**
- Placa mãe compatível com LGA 1700
- Pelo menos 8GB RAM (recomendado 16GB+)
- SSD NVMe para melhor performance
- Fonte de alimentação adequada (750W+ recomendado)

### 🔧 **Configurações BIOS (F13)**
- **Secure Boot**: Desabilitado
- **Fast Boot**: Desabilitado
- **CSM**: Desabilitado
- **VT-d**: Desabilitado (se causar problemas)
- **Above 4G Decoding**: Habilitado
- **Resizable BAR**: Habilitado
- **XMP/DOCP**: Habilitado (para DDR5)
- **Intel SpeedStep**: Habilitado
- **Intel Turbo Boost**: Habilitado
- **Hyper-Threading**: Habilitado

## 🚨 **Avisos Importantes**

### ⚠️ **Antes de Usar**
1. **Backup**: Sempre faça backup da sua EFI atual
2. **Serial Numbers**: Gere novos serial numbers únicos
3. **SMBIOS**: Configure o SMBIOS adequado para seu hardware
4. **Teste**: Teste em ambiente controlado primeiro

### 🔒 **Segurança**
- Esta EFI é específica para o hardware listado
- Não use em hardware diferente sem adaptações
- Mantenha sempre backups atualizados

## 📞 **Suporte**

### 🐛 **Problemas Conhecidos**
- Alguns jogos podem ter problemas com Metal
- Sleep pode não funcionar perfeitamente
- Algumas funcionalidades específicas do macOS podem estar limitadas

### 💡 **Dicas de Otimização**
- Use ferramentas como Hackintool para mapear USB
- Configure corretamente o SMBIOS
- Monitore temperaturas e performance
- Mantenha os kexts atualizados

## 📝 **Changelog**

### **v5163**
- Atualização para Clover 5163
- Melhorias na compatibilidade com Sequoia
- Otimizações para RX 6900 XT
- Correções de USB e Power Management

---

**⚠️ Disclaimer**: Este projeto é apenas para fins educacionais. O uso de macOS em hardware não-Apple pode violar os termos de serviço da Apple. Use por sua própria conta e risco.

**📅 Última Atualização**: Outubro 2025
**🔧 Versão Clover**: 5163
**💻 Hardware**: Aorus Z790 Elite AX + RX 6900 XT + i9-13900K