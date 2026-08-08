<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=00FF99&center=true&vCenter=true&width=750&lines=Cyber+Security+Student;Network+Security+Engineer+(In+Training);TCP%2FIP+%7C+OS+Internals+%7C+Enterprise+Security;Building+Security+Knowledge+from+Packets+to+Systems" />

<p>
<em>"Understand the system before securing it."</em>
<br>
<sub>从数据包到系统，构建对安全的理解。</sub>
</p>

</div>

---

### 👤 关于我

```text
> 身份       : 计算机网络专业学生 | 渗透测试方向
> 动手能力   : Python 自动化攻击脚本开发 · Scapy 协议构造 · 多线程扫描
> 研究       : TCP/IP 协议栈 · Windows 认证机制（NTLM/Kerberos） · 内网渗透
> 学习方法   : 以攻促防，通过亲手构造攻击包来理解协议底层，逆向防御思路
> 当前阶段   : 协议攻击实战 ✅ → Windows 提权实战 🚀
> 目标       : 企业安全工程师（红蓝兼备）
```

- 目前正在深入学习 Windows 认证机制，包括 NTLM、Kerberos、Token 模型、权限控制以及 Active Directory 安全。
- 坚信“实验驱动学习”，通过自建实验环境验证认证流程、权限模型以及安全检测机制。
- 寻求安全工程 / 内网安全方向的实习与交流机会。

---

## 🗺️ 安全学习路线

```text
┌─────────────────────────────────────┐
│              网络基础               │   TCP/IP · ARP · VLAN · Routing
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│              协议分析               │   Wireshark · Packet Analysis
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│              操作系统原理           │   Windows/Linux Internals
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│          Windows 安全机制           │   Token · ACL · LSASS · UAC
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│       Active Directory 安全         │   Kerberos · NTLM · GPO
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│            企业内网安全             │   Attack Surface Analysis · Detection
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│            安全监控与检测           │   SIEM · Sysmon · Monitoring
└─────────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│            企业安全架构             │   Zero Trust · Privileged Access
└─────────────────────────────────────┘
```

---

### 🛠️ 技能栈

| 分类 | 技术栈 |
| :--- | :--- |
| **网络协议** | TCP/IP、ARP、ICMP、DNS、DHCP、UDP |
| **协议分析** | Wireshark、tcpdump、Scapy |
| **Python 自动化** | Scapy（协议构造）、多线程并发、subprocess（外部工具调用） |
| **操作系统** | Linux（Kali/Ubuntu）、Windows（7/10/Server） |
| **身份认证** | NTLM、Kerberos、LDAP |
| **域安全** | Active Directory、BloodHound |
| **安全工具** | Nmap、Metasploit、Hydra、Burp Suite（基础） |

### 常用工具与平台

<p>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/tcpdump-000000?style=flat-square&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-000000?style=flat-square&logo=nmap&logoColor=white" />
  <img src="https://img.shields.io/badge/BloodHound-C83737?style=flat-square&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Sysmon-0078D4?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows_Event_Logs-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" />
</p>

---

### 📚 Recently Labs

```text
✅ ARP 协议分析 + 手写 ARP 欺骗攻击脚本（Scapy）
✅ TCP SYN 半开端口扫描器（多线程版，自研）
✅ UDP/ICMP 协议探测脚本
✅ Python 交互式 Nmap 调用工具
✅ Scapy sniff() 自动化抓包与协议解析
✅ Wireshark + tcpdump 手动流量分析
🔲 Windows 权限提升实战（进行中）
```

---


**当前实验环境：**

- Windows Server / Linux 靶机 + Kali 攻击机，用于协议攻击与提权练习。
- 下一步计划搭建 Windows 域环境，深入内网横向移动与域渗透。

```text
homelab/
├── network-infrastructure/  网络基础设施层
│   ├── firewall             防火墙隔离策略
│   ├── vlan                 VLAN 划分与路由
│   └── routing              静态/动态路由配置
├── windows-domain/          企业内网域环境
│   ├── lab.example.local    域控制器
│   └── client-01/02         域内主机
├── linux-server/            Linux 服务器 (SSH, auditd)
├── logging/                 Sysmon + ELK Stack 日志采集与分析
└── security-testing/        隔离测试环境 (用于安全验证)
```

**通过实验环境深入理解：**
- Kerberos / NTLM 认证流程及其潜在风险
- 域内权限关系分析与安全检测方案
- 网络层隔离与内网安全架构设计

---

### 🚀 核心项目

| 项目名称 | 描述 | 状态 |
| :--- | :--- | :---: |
| **[Network-Engineering-Notes](https://github.com/Cyph3rLab/Network-Engineering-Notes)** | **一站式知识库**：网络协议分析 + 内网渗透实战手册 + Python 攻击脚本合集 | 🔄 WIP |
| **[cypher3r-arch-guide](https://github.com/Cyph3rLab/cypher3r-arch-guide)** | **Arch Linux 笔记**：不讲安装步骤，只讲配置决策、踩坑记录与底层原理 | 🔄 WIP |
| **渗透测试速查表** | Scapy 协议速查表 · 多线程扫描骨架 · 发包模板 | 🔄 WIP |
| **Windows 提权实战笔记** | Windows 服务/注册表/Potato 家族提权手法研究与复现 | 🔄 WIP |
| **企业安全实验环境** | VMware 虚拟化搭建的 Windows 域环境与内网渗透靶场 | 🔄 WIP |

---

## 📊 GitHub 统计

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Cyph3rLab&theme=tokyonight&hide_border=true" height="160" />
</p>

---

## 🧭 Security Philosophy

> "Security is not only about finding vulnerabilities,
> but understanding how systems communicate, authenticate and defend."

从数据包到操作系统，从身份认证到企业架构，持续构建对安全系统的深度理解。

---

## 📫 联系方式

<p>
  <a href="mailto:<YOUR_EMAIL>"><img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>


