# 🖧 Trắc Nghiệm Quản Trị Hệ Thống Mạng

> Ứng dụng ôn tập trắc nghiệm môn **Quản Trị Hệ Thống Mạng** — 160 câu hỏi, 8 chương, không cần backend, chạy hoàn toàn trên trình duyệt.

🌐 **Demo:** [https://ThuanPhats.github.io/QTHTM/](https://ThuanPhats.github.io/QTHTM/)

---

## 📋 Giới thiệu

Đây là bộ câu hỏi trắc nghiệm được thiết kế để giúp sinh viên ôn tập và tự kiểm tra kiến thức môn **Quản Trị Hệ Thống Mạng**. Ứng dụng hoạt động như một game quiz, hiển thị từng câu hỏi một, cho phép người dùng chọn đáp án và nhận phản hồi ngay lập tức.

---

## 📚 Nội dung câu hỏi

Bộ đề gồm **160 câu trắc nghiệm** chia thành **8 chương**, bao phủ toàn bộ chương trình lý thuyết:

| Chương | Tên chủ đề | Số câu |
|--------|-----------|--------|
| Chương 1 | Giới thiệu về Quản Trị Hệ Thống Mạng | 20 |
| Chương 2 | Các thành phần của hệ thống | 10 |
| Chương 3 | Quản trị máy chủ | 20 |
| Chương 4 | Quản trị người dùng | 20 |
| Chương 5 | Mô hình quản trị mạng và hệ thống | 20 |
| Chương 6 | Cấu hình và duy trì hệ thống | 20 |
| Chương 7 | Các dịch vụ mức ứng dụng | 20 |
| Chương 8 | Các dịch vụ mức mạng | 20 |
| **Tổng** | | **150 câu** |

---

## 🧠 Chi tiết nội dung từng chương

### Chương 1 — Giới thiệu (20 câu)
Các khái niệm cơ bản về quản trị hệ thống mạng:
- Định nghĩa, vai trò và mục tiêu của quản trị viên mạng
- Chiến lược và nguyên lý quản trị hệ thống
- Đạo đức trong quản trị (bảo mật thông tin, quyền riêng tư)
- Công cụ giám sát, tự động hóa (automation, AI)
- Khái niệm SLA (Service Level Agreement)

### Chương 2 — Các thành phần hệ thống (10 câu)
Phần cứng và phần mềm cấu thành hệ thống:
- CPU, RAM, HDD/SSD, GPU, Cache
- Card mạng (NIC), Switch, Router, Firewall
- UPS (nguồn điện dự phòng), BIOS/UEFI
- Hệ điều hành máy chủ (Windows Server, Linux)

### Chương 3 — Quản trị máy chủ (20 câu)
Triển khai và vận hành máy chủ:
- Các loại server: DNS, DHCP, Web, FTP, Mail, Backup
- Ảo hóa: Hypervisor, VM, Snapshot, RAID
- Lưu trữ: SAN, NAS
- Tính sẵn sàng cao: Load Balancing, HA, Clustering, Failover
- Datacenter, Monitoring server

### Chương 4 — Quản trị người dùng (20 câu)
Quản lý tài khoản và phân quyền:
- Active Directory, LDAP, Kerberos
- Group Policy, Domain, Workgroup, OU
- Phân quyền: RBAC, Principle of Least Privilege
- Bảo mật: MFA, Password Policy, Audit Log, SSO
- Vòng đời tài khoản: tạo, vô hiệu hóa, xóa

### Chương 5 — Mô hình quản trị mạng và hệ thống (20 câu)
Kiến trúc mạng và điện toán đám mây:
- Mô hình Client-Server, P2P
- Cloud Computing: IaaS, PaaS, SaaS
- Private cloud, Public cloud, Hybrid cloud
- Giám sát mạng: SNMP, Syslog, NMS, Nagios
- Kỹ thuật mạng: VLAN, VPN, NAT, QoS, Bandwidth, Latency
- Mô hình OSI (7 tầng), TCP/IP

### Chương 6 — Cấu hình và duy trì hệ thống (20 câu)
Vận hành và bảo trì hệ thống:
- Configuration Management, Change Management
- Công cụ tự động hóa: Ansible, Puppet, Chef
- Bảo trì phòng ngừa, Disk defragmentation
- Backup: Full backup, Incremental backup, quy tắc 3-2-1
- Phục hồi thảm họa: DRP, RTO, RPO
- DevOps: IaC, Terraform, CI/CD, Docker, Kubernetes

### Chương 7 — Các dịch vụ mức ứng dụng (20 câu)
Giao thức và dịch vụ tầng ứng dụng:
- Web: HTTP, HTTPS, SSL/TLS
- Email: SMTP, POP3, IMAP
- Truyền file: FTP, SFTP
- Truy cập từ xa: SSH, Telnet, RDP
- Hạ tầng: NTP, SNMP, Proxy, Reverse Proxy, CDN
- Kiến trúc hiện đại: WAF, API Gateway, Microservices, Load Balancer

### Chương 8 — Các dịch vụ mức mạng (20 câu)
Giao thức và kỹ thuật tầng mạng:
- Địa chỉ IP: IPv4 (32-bit), IPv6 (128-bit), Subnet mask
- Default Gateway, ARP, ICMP (Ping)
- Cổng dịch vụ: Port 80 (HTTP), 443 (HTTPS), 22 (SSH), 25 (SMTP)
- Giao thức vận chuyển: TCP (tin cậy), UDP (nhanh)
- Định tuyến: Static routing, Dynamic routing, RIP/OSPF/BGP
- Firewall rules, MAC address (48-bit)

---

## 🎮 Tính năng ứng dụng

| Tính năng | Mô tả |
|-----------|-------|
| 🎯 **Chế độ luyện tập** | Chọn tất cả hoặc từng chương riêng lẻ |
| 🔀 **Xáo trộn thông minh** | Câu hỏi VÀ đáp án đều xáo ngẫu nhiên mỗi phiên |
| ⚡ **Phản hồi tức thì** | Đúng → xanh lá, Sai → đỏ, hiện đáp án đúng |
| 📊 **Tính điểm** | +20 điểm mỗi câu đúng, −10 điểm mỗi câu sai |
| 🏆 **Bảng xếp hạng** | Lưu điểm cao vào localStorage, có thể sort |
| 📋 **Lịch sử thi** | Xem lại 10 phiên thi gần nhất |
| 📱 **Responsive** | Hoạt động tốt trên điện thoại (375px+) |
| 🌙 **Dark mode** | Giao diện tối hoàn toàn, bảo vệ mắt |

---

## 🚀 Chạy ứng dụng

### Cách 1: Trực tiếp trên GitHub Pages
Truy cập: **[https://ThuanPhats.github.io/QTHTM/](https://ThuanPhats.github.io/QTHTM/)**

### Cách 2: Chạy offline
1. Tải file `docs/index.html` về máy
2. Mở bằng bất kỳ trình duyệt nào (Chrome, Firefox, Edge…)
3. Không cần internet, không cần cài thêm gì

---

## 🏗 Cấu trúc dự án

```
QTHTM/
└── docs/
    └── index.html    ← Toàn bộ ứng dụng (HTML + CSS + JS inline)
```

> **Zero dependency** — không Bootstrap, không jQuery, không React, không CDN.  
> Một file duy nhất, chạy được ở mọi nơi.

---

## 🗂 Cách lưu trữ dữ liệu

Ứng dụng dùng `localStorage` của trình duyệt, không có backend:

| Key | Nội dung | Giới hạn |
|-----|---------|---------|
| `qthtm_leaderboard` | Danh sách kết quả thi (tất cả người dùng) | Không giới hạn |
| `qthtm_history` | Lịch sử phiên thi | Tối đa 50 bản ghi (FIFO) |

> ⚠️ Dữ liệu lưu trên trình duyệt của từng thiết bị. Xóa cache trình duyệt sẽ mất dữ liệu.

---

## 📐 Công thức tính điểm

```
Điểm ban đầu = 0
Trả lời đúng → +20 điểm
Trả lời sai  → −10 điểm
Điểm có thể âm (nếu sai nhiều)

Độ chính xác (%) = (Số câu đúng / Tổng số câu) × 100
```

---

## 🛠 Công nghệ sử dụng

- **HTML5** — cấu trúc trang
- **CSS3** — giao diện dark mode, animation, responsive
- **JavaScript (ES6+)** — logic quiz, shuffle, localStorage
- **GitHub Pages** — hosting tĩnh miễn phí

---

## 📖 Hướng dẫn sử dụng

1. **Nhập tên** của bạn (tối thiểu 2 ký tự)
2. **Chọn chương** muốn ôn tập (hoặc "Tất cả" để thi toàn bộ)
3. Nhấn **Bắt Đầu** 🚀
4. Đọc câu hỏi → chọn đáp án → xem kết quả ngay
5. Nhấn **Câu tiếp theo →** để tiếp tục
6. Sau khi hết câu → xem **kết quả tổng** và so sánh với **bảng xếp hạng**

---

## 👨‍💻 Tác giả

**ThuanPhats** — Sinh viên ngành Công Nghệ Thông Tin

---

*Chúc bạn ôn tập hiệu quả! 🎓*
