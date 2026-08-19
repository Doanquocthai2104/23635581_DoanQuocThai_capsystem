# 23635581_DoanQuocThai_capsystem
hoc thuc hanh buoi 1

## Các yếu điểm và hạn chế của hệ thống hiện tại

| STT | Yếu điểm / hạn chế | Vấn đề cụ thể |
|---|---|---|
| 1 | **Phân công tài xế thủ công** | Việc tìm và phân công tài xế chủ yếu do nhân viên thực hiện, mất thời gian và khó xử lý khi số lượng chuyến tăng. |
| 2 | **Khó theo dõi trạng thái chuyến đi** | Khách hàng khó biết đang tìm tài xế, tài xế nào nhận chuyến, tài xế đã đến chưa hay chuyến đang ở trạng thái nào. |
| 3 | **Thanh toán chưa được quản lý tập trung** | Thông tin thanh toán chưa được quản lý thống nhất, gây khó khăn cho việc tra cứu và quản lý giao dịch. |
| 4 | **Khả năng mở rộng hạn chế** | Hệ thống hiện tại khó đáp ứng khi số lượng khách hàng và tài xế tăng lên. |
| 5 | **Phụ thuộc vào tổng đài / ứng dụng đơn giản** | Khách hàng chỉ có thể liên hệ tổng đài hoặc sử dụng ứng dụng đơn giản, chưa có nền tảng đặt xe đầy đủ. |
| 6 | **Xử lý tìm tài xế chưa tự động** | Khi tài xế được đề xuất không phản hồi hoặc từ chối, hệ thống hiện tại chưa có cơ chế tự động tìm tài xế khác được mô tả. |
| 7 | **Thiếu khả năng theo dõi vị trí tài xế** | Chưa có cơ chế quản lý vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và dự kiến thời gian đến. |
| 8 | **Khó quản lý hoạt động vận hành** | Bộ phận vận hành gặp khó khăn trong việc theo dõi chuyến đi và quản lý hoạt động khi quy mô hệ thống tăng. |
| 9 | **Khả năng phát triển tính năng mới hạn chế** | Hệ thống hiện tại chưa đáp ứng tốt yêu cầu phát triển thêm các loại dịch vụ, phương thức thanh toán hoặc kênh thông báo trong tương lai. |       



## Tại sao cần một hệ thống mới?

Hệ thống mới được xây dựng nhằm khắc phục những hạn chế của hệ thống hiện tại và đáp ứng nhu cầu phát triển của doanh nghiệp.

1. **Tự động hóa việc tìm và phân công tài xế:** Giảm sự phụ thuộc vào nhân viên vận hành và rút ngắn thời gian tìm tài xế.

2. **Cải thiện trải nghiệm khách hàng:** Cho phép khách hàng đặt xe, theo dõi trạng thái chuyến đi và biết thông tin tài xế theo thời gian thực.

3. **Quản lý thanh toán tập trung:** Quản lý thông tin và kết quả giao dịch một cách thống nhất, hỗ trợ cả tiền mặt và thanh toán điện tử.

4. **Nâng cao hiệu quả vận hành:** Nhân viên có thể quản lý khách hàng, tài xế, phương tiện và chuyến đi trên một hệ thống.

5. **Hỗ trợ mở rộng hệ thống:** Có kiến trúc linh hoạt, cho phép hệ thống phục vụ nhiều khách hàng và tài xế hơn khi nhu cầu tăng.

6. **Dễ dàng phát triển trong tương lai:** Có thể bổ sung loại dịch vụ, phương thức thanh toán và kênh thông báo mới mà không phải xây dựng lại toàn bộ hệ thống.
### Mục tiêu của hệ thống mới

> Xây dựng một nền tảng CAB hiện đại, tự động và có khả năng mở rộng, hỗ trợ toàn bộ quy trình từ **đặt xe → tìm tài xế → thực hiện chuyến → tính cước → thanh toán → đánh giá**.



## Stakeholder chính
   
| # | Stakeholder | Vai trò | Tầm quan trọng |
|---|---|---|---|
| 1 | **Khách hàng (Customer)** | Đặt xe, theo dõi chuyến đi, thanh toán và đánh giá tài xế. | **Rất quan trọng** – Là người sử dụng trực tiếp hệ thống và tạo ra các yêu cầu đặt xe. |
| 2 | **Tài xế (Driver)** | Nhận chuyến, thực hiện chuyến và cập nhật trạng thái. | **Rất quan trọng** – Là bên trực tiếp cung cấp dịch vụ và quyết định khả năng thực hiện chuyến. |
| 3 | **Nhân viên vận hành (Operation Staff)** | Quản lý khách hàng, tài xế, phương tiện và chuyến đi. | **Rất quan trọng** – Đảm bảo hoạt động vận hành được quản lý và xử lý sự cố kịp thời. |
| 4 | **Bộ phận Tài chính (Finance/Accounting)** | Theo dõi thanh toán, giao dịch và doanh thu. | **Quan trọng** – Đảm bảo các giao dịch, doanh thu và đối soát được quản lý chính xác. |
| 5 | **Ban giám đốc (Management)** | Theo dõi báo cáo và đưa ra quyết định kinh doanh. | **Quan trọng** – Xác định mục tiêu kinh doanh và đánh giá hiệu quả của hệ thống. |
| 6 | **Nhà cung cấp thanh toán (Payment Provider)** | Xử lý các giao dịch thanh toán điện tử. | **Quan trọng** – Đảm bảo thanh toán điện tử được thực hiện an toàn và chính xác. |
| 7 | **Nhà cung cấp thông báo (Notification Provider)** | Gửi thông báo đến khách hàng và tài xế. | **Quan trọng** – Đảm bảo thông tin về chuyến đi và thanh toán được truyền đến người dùng. |
| 8 | **Nhà cung cấp bản đồ/vị trí (Map & Location Provider)** | Cung cấp dữ liệu vị trí và hỗ trợ tìm tài xế. | **Quan trọng** – Hỗ trợ xác định vị trí và tìm tài xế phù hợp với khách hàng. |




## Ma trận Stakeholder – CAB System

```mermaid
quadrantChart
    title Ma trận Stakeholder - CAB System
    x-axis Mức độ quan tâm thấp --> Mức độ quan tâm cao
    y-axis Mức độ ảnh hưởng thấp --> Mức độ ảnh hưởng cao
    quadrant-1 Quản lý chặt chẽ
    quadrant-2 Duy trì hài lòng
    quadrant-3 Theo dõi
    quadrant-4 Duy trì thông tin

    "Ban giám đốc": [0.85, 0.90]
    "Nhân viên vận hành": [0.82, 0.80]
    "Tài chính/Kế toán": [0.75, 0.70]
    "Nhà cung cấp thanh toán": [0.60, 0.65]
    "Khách hàng": [0.85, 0.35]
    "Tài xế": [0.80, 0.30]
    "Nhà cung cấp thông báo": [0.45, 0.25]
    "Nhà cung cấp bản đồ/vị trí": [0.50, 0.30]
```
# Phạm vi cốt lõi trong 7 tuần

| Vấn đề cốt lõi | Nội dung cần giải quyết |
|---|---|
| **Đặt xe** | Khách hàng nhập điểm đón, điểm đến, chọn loại xe và gửi yêu cầu. |
| **Tìm tài xế** | Hệ thống tự động tìm tài xế phù hợp và xử lý khi tài xế từ chối hoặc không phản hồi. |
| **Thực hiện chuyến** | Tài xế nhận chuyến và cập nhật trạng thái đến khi hoàn thành. |
| **Theo dõi chuyến** | Khách hàng theo dõi trạng thái chuyến và thông tin tài xế. |
| **Tính cước & thanh toán** | Tính số tiền phải trả, hỗ trợ tiền mặt và thanh toán điện tử. |
| **Thông báo** | Thông báo các sự kiện quan trọng cho khách hàng và tài xế. |
| **Quản lý vận hành** | Nhân viên quản lý khách hàng, tài xế, phương tiện và chuyến đi. |
| **Bảo mật & dữ liệu** | Xác thực, phân quyền và bảo vệ thông tin cá nhân, vị trí, giao dịch. |


# Business Goals

| ID | Business Goal |
|---|---|
| **BG-01** | Cung cấp quy trình đặt xe nhanh chóng và thuận tiện cho khách hàng. |
| **BG-02** | Tự động hóa quá trình tìm và phân công tài xế, giảm sự phụ thuộc vào nhân viên vận hành. |
| **BG-03** | Đảm bảo chuyến xe được thực hiện và quản lý đầy đủ từ khi tài xế nhận chuyến đến khi hoàn thành. |
| **BG-04** | Cải thiện khả năng theo dõi chuyến và trải nghiệm của khách hàng. |
| **BG-05** | Quản lý việc tính cước và thanh toán chính xác, an toàn và thuận tiện. |
| **BG-06** | Đảm bảo khách hàng và tài xế nhận được thông tin kịp thời về chuyến đi và thanh toán. |
| **BG-07** | Nâng cao hiệu quả quản lý và giám sát hoạt động vận hành của doanh nghiệp. |
| **BG-08** | Đảm bảo hệ thống hoạt động an toàn và bảo vệ dữ liệu của người dùng và doanh nghiệp. |

# Business Requirements

| ID | Business Requirement | Business Goal |
|---|---|---|
| **BR-01** | Hệ thống phải hỗ trợ khách hàng tạo yêu cầu đặt xe dựa trên điểm đón, điểm đến và loại xe. | BG-01 |
| **BR-02** | Hệ thống phải tự động tìm và phân công tài xế phù hợp với yêu cầu đặt xe. | BG-02 |
| **BR-03** | Hệ thống phải hỗ trợ quản lý toàn bộ quá trình thực hiện chuyến xe. | BG-03 |
| **BR-04** | Hệ thống phải cung cấp thông tin trạng thái chuyến và tài xế cho khách hàng. | BG-04 |
| **BR-05** | Hệ thống phải tính số tiền khách hàng phải trả và hỗ trợ các phương thức thanh toán được doanh nghiệp chấp nhận. | BG-05 |
| **BR-06** | Hệ thống phải gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng. | BG-06 |
| **BR-07** | Hệ thống phải cung cấp công cụ để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi. | BG-07 |
| **BR-08** | Hệ thống phải xác thực người dùng, kiểm soát quyền truy cập và bảo vệ dữ liệu quan trọng. | BG-08 |

# Functional Requirements


| Business Requirement | Functional Requirements |
|---|---|
| **BR-01: Đặt xe** | • **FR-01.1:** Cho phép khách hàng nhập điểm đón và điểm đến.<br>• **FR-01.2:** Cho phép khách hàng chọn loại xe và gửi yêu cầu đặt xe.<br>• **FR-01.3:** Ghi nhận yêu cầu và tạo chuyến đi. |
| **BR-02: Tìm tài xế** | • **FR-02.1:** Xác định tài xế đang sẵn sàng và phù hợp.<br>• **FR-02.2:** Ưu tiên tài xế dựa trên vị trí và tiêu chí vận hành.<br>• **FR-02.3:** Gửi yêu cầu chuyến và ghi nhận phản hồi của tài xế.<br>• **FR-02.4:** Tiếp tục tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.<br>• **FR-02.5:** Thông báo cho khách hàng khi không tìm được tài xế. |
| **BR-03: Thực hiện chuyến** | • **FR-03.1:** Cho phép tài xế nhận chuyến.<br>• **FR-03.2:** Hệ thống cho phép tài xế cập nhật các trạng thái chính của chuyến từ khi đến điểm đón đến khi hoàn thành.<br>• **FR-03.3:** Ghi nhận và lưu trạng thái hoàn thành chuyến. |
| **BR-04: Theo dõi chuyến** | • **FR-04.1:** Hiển thị trạng thái hiện tại của chuyến cho khách hàng.<br>• **FR-04.2:** Hiển thị thông tin tài xế và phương tiện.<br>• **FR-04.3:** Hệ thống cập nhật trạng thái chuyến cho khách hàng khi có thay đổi. |
| **BR-05: Tính cước & thanh toán** | • **FR-05.1:** Tính số tiền khách hàng phải trả sau khi chuyến hoàn thành.<br>• **FR-05.2:** Hỗ trợ thanh toán bằng tiền mặt và thanh toán điện tử.<br>• **FR-05.3:** Ghi nhận trạng thái và kết quả giao dịch.<br>• **FR-05.4:** Thông báo kết quả thanh toán cho khách hàng. |
| **BR-06: Thông báo** | • **FR-06.1:** Gửi thông báo khi yêu cầu đặt xe được tiếp nhận.<br>• **FR-06.2:** Gửi thông báo khi tài xế nhận chuyến và khi trạng thái chuyến thay đổi.<br>• **FR-06.3:** Gửi thông báo về kết quả thanh toán.<br>• **FR-06.4:** Gửi thông báo cho tài xế về chuyến mới hoặc thay đổi liên quan đến chuyến. |
| **BR-07: Quản lý vận hành** | • **FR-07.1:** Cho phép nhân viên quản lý khách hàng, tài xế và phương tiện.<br>• **FR-07.2:** Cho phép nhân viên theo dõi chuyến đang diễn ra và trạng thái tài xế.<br>• **FR-07.3:** Cho phép nhân viên tra cứu lịch sử chuyến và giao dịch.<br>• **FR-07.4:** Hỗ trợ nhân viên xử lý các trường hợp chuyến bị lỗi. |
| **BR-08: Bảo mật & dữ liệu** | • **FR-08.1:** Yêu cầu xác thực người dùng trước khi sử dụng chức năng yêu cầu tài khoản.<br>• **FR-08.2:** Phân quyền người dùng theo vai trò.<br>• **FR-08.3:** Bảo vệ thông tin cá nhân, dữ liệu vị trí và dữ liệu giao dịch.<br>• **FR-08.4:** Lưu vết các thao tác quản trị quan trọng. |


# Danh sách Use Case CAB System

## 1. Khách hàng

| ID | Use Case |
|---|---|
| **UC01** | Đăng ký tài khoản |
| **UC02** | Đăng nhập |
| **UC03** | Quản lý thông tin cá nhân |
| **UC04** | Đặt xe |
| **UC05** | Theo dõi chuyến đi |
| **UC06** | Xem lịch sử chuyến đi |
| **UC07** | Thanh toán chuyến đi |
| **UC08** | Đánh giá tài xế |


## 2. Tài xế

| ID | Use Case |
|---|---|
| **UC02** | Đăng nhập |
| **UC09** | Quản lý thông tin tài xế và phương tiện |
| **UC10** | Quản lý trạng thái hoạt động và vị trí |
| **UC11** | Chấp nhận / Từ chối chuyến |
| **UC12** | Cập nhật trạng thái chuyến |



## 3. Nhân viên vận hành

| ID | Use Case |
|---|---|
| **UC02** | Đăng nhập |
| **UC13** | Quản lý khách hàng |
| **UC14** | Quản lý tài xế |
| **UC15** | Quản lý phương tiện |
| **UC16** | Theo dõi chuyến đi |
| **UC17** | Tra cứu lịch sử giao dịch |
| **UC18** | Xử lý sự cố chuyến đi |


## 4. Ban lãnh đạo

| ID | Use Case |
|---|---|
| **UC02** | Đăng nhập |
| **UC19** | Xem báo cáo hoạt động |


## 5. Hệ thống bên ngoài

| ID | Use Case | Actor |
|---|---|---|
| **UC20** | Xử lý thanh toán điện tử | Nhà cung cấp thanh toán |
| **UC21** | Gửi thông báo | Nhà cung cấp thông báo |


##  Tổng hợp

| Nhóm | Use Case |
|---|---:|
| Khách hàng | 8 |
| Tài xế | 5 *(bao gồm UC02 dùng chung)* |
| Nhân viên vận hành | 7 *(bao gồm UC02 dùng chung)* |
| Ban lãnh đạo | 2 *(bao gồm UC02 dùng chung)* |
| Hệ thống bên ngoài | 2 |
| **Tổng số Use Case thực tế** | **21** |

### Các Use Case dùng chung

- **UC02 – Đăng nhập:** Khách hàng, Tài xế, Nhân viên vận hành, Ban lãnh đạo.
- **UC20 – Xử lý thanh toán điện tử:** được sử dụng khi khách hàng thanh toán bằng phương thức điện tử.
- **UC21 – Gửi thông báo:** phục vụ thông báo cho khách hàng, tài xế và các sự kiện quan trọng của hệ thống.
## Use Case Diagram – CAB System

```mermaid
flowchart LR

    %% =========================
    %% ACTORS
    %% =========================

    Customer[" Khách hàng"]
    Driver[" Tài xế"]
    Staff[" Nhân viên vận hành"]
    Management[" Ban lãnh đạo"]
    Payment[" Nhà cung cấp thanh toán"]
    Notification[" Nhà cung cấp thông báo"]

    %% =========================
    %% CAB SYSTEM
    %% =========================

    subgraph CAB["CAB SYSTEM"]

        %% ===== CUSTOMER =====
        UC01(["UC01 - Đăng ký tài khoản"])
        UC02(["UC02 - Đăng nhập"])
        UC03(["UC03 - Quản lý thông tin cá nhân"])
        UC04(["UC04 - Đặt xe"])
        UC05(["UC05 - Theo dõi chuyến đi"])
        UC06(["UC06 - Xem lịch sử chuyến đi"])
        UC07(["UC07 - Thanh toán chuyến đi"])
        UC08(["UC08 - Đánh giá tài xế"])

        %% ===== DRIVER =====
        UC09(["UC09 - Quản lý thông tin tài xế và phương tiện"])
        UC10(["UC10 - Quản lý trạng thái hoạt động và vị trí"])
        UC11(["UC11 - Chấp nhận / Từ chối chuyến"])
        UC12(["UC12 - Cập nhật trạng thái chuyến"])

        %% ===== OPERATION STAFF =====
        UC13(["UC13 - Quản lý khách hàng"])
        UC14(["UC14 - Quản lý tài xế"])
        UC15(["UC15 - Quản lý phương tiện"])
        UC16(["UC16 - Theo dõi chuyến đi"])
        UC17(["UC17 - Tra cứu lịch sử giao dịch"])
        UC18(["UC18 - Xử lý sự cố chuyến đi"])

        %% ===== MANAGEMENT =====
        UC19(["UC19 - Xem báo cáo hoạt động"])

        %% ===== EXTERNAL SERVICES =====
        UC20(["UC20 - Xử lý thanh toán điện tử"])
        UC21(["UC21 - Gửi thông báo"])

    end

    %% =========================
    %% CUSTOMER ASSOCIATIONS
    %% =========================

    Customer --- UC01
    Customer --- UC02
    Customer --- UC03
    Customer --- UC04
    Customer --- UC05
    Customer --- UC06
    Customer --- UC07
    Customer --- UC08

    %% =========================
    %% DRIVER ASSOCIATIONS
    %% =========================

    Driver --- UC02
    Driver --- UC09
    Driver --- UC10
    Driver --- UC11
    Driver --- UC12

    %% =========================
    %% OPERATION STAFF ASSOCIATIONS
    %% =========================

    Staff --- UC02
    Staff --- UC13
    Staff --- UC14
    Staff --- UC15
    Staff --- UC16
    Staff --- UC17
    Staff --- UC18

    %% =========================
    %% MANAGEMENT ASSOCIATIONS
    %% =========================

    Management --- UC02
    Management --- UC19

    %% =========================
    %% EXTERNAL SYSTEM ASSOCIATIONS
    %% =========================

    Payment --- UC20

    Notification --- UC21

    %% =========================
    %% INCLUDE RELATIONSHIPS
    %% =========================

    UC07 -.->|<<include>>| UC20

    UC04 -.->|<<include>>| UC21
    UC07 -.->|<<include>>| UC21
    UC11 -.->|<<include>>| UC21
    UC12 -.->|<<include>>| UC21
    UC18 -.->|<<include>>| UC21
