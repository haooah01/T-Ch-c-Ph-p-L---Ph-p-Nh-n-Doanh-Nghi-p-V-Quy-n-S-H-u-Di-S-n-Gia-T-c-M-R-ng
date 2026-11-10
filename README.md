# Legal Organization, Business Entities, and Expanded Family Heritage Ownership Rights

# Hệ thống phân loại và tra cứu thuật ngữ pháp lý

## Legal Entity & Legal Identity Taxonomy — Vietnam

Hệ thống này phân loại và liên kết các thuật ngữ về **pháp lý, pháp nhân, chủ thể sở hữu, đại diện, tài khoản, tài sản và quyền kiểm soát**. Mục tiêu không chỉ là lập danh sách tên công ty, mà là xây dựng hệ thống phân cấp danh tính và chủ thể pháp lý để có thể truy ngược trong từng tình huống thực tế:

- Ai hoặc tổ chức nào sở hữu tài sản?
- Chủ thể nào có tư cách pháp nhân?
- Ai có quyền đại diện và ký kết?
- Ai có quyền quản lý, điều phối tiền hoặc thực hiện giao dịch?
- Tài khoản thuộc chủ thể nào?
- Quyền sở hữu, quyền sử dụng và quyền kiểm soát khác nhau ra sao?
- Văn bản nào xác lập các quyền đó?

> Đây là tài liệu khung nghiên cứu và thiết kế dữ liệu. Mỗi kết luận pháp lý cụ thể cần được đối chiếu với văn bản gốc, tình trạng hiệu lực và chứng cứ liên quan.

## 1. Bản đồ mục lục tổng thể

| STT | Nhóm | Nội dung cần lập chỉ mục |
|---:|---|---|
| 01 | Legal Subjects | Chủ thể pháp luật, cá nhân, tổ chức |
| 02 | Legal Entities | Pháp nhân thương mại, phi thương mại |
| 03 | Business Entities | Công ty TNHH, cổ phần, hợp danh, doanh nghiệp tư nhân |
| 04 | Legal Identity | Tên pháp lý, tên giao dịch, tên viết tắt, mã số doanh nghiệp |
| 05 | Ownership | Chủ sở hữu, cổ đông, thành viên góp vốn, chủ sở hữu hưởng lợi |
| 06 | Governance | Hội đồng thành viên, Hội đồng quản trị, Đại hội đồng cổ đông |
| 07 | Representation | Người đại diện theo pháp luật, đại diện theo ủy quyền |
| 08 | Authority | Thẩm quyền, quyền hạn, phạm vi đại diện |
| 09 | Contracts | Bên mua, bên bán, bên thuê, bên cho thuê, bên bảo lãnh |
| 10 | Assets | Tài sản, quyền tài sản, động sản, bất động sản |
| 11 | Banking | Chủ tài khoản, tài khoản thanh toán, người được ủy quyền |
| 12 | Accounting | Tài sản kế toán, vốn chủ sở hữu, nợ phải trả, doanh thu |
| 13 | Taxation | Mã số thuế, nghĩa vụ thuế, hóa đơn, kê khai |
| 14 | Liability | Trách nhiệm dân sự, nghĩa vụ tài chính, trách nhiệm pháp lý |
| 15 | Legal Status | Thành lập, hoạt động, tạm ngừng, giải thể, phá sản |

Đây là cấu trúc phân loại ban đầu, không phải danh mục đầy đủ tất cả thuật ngữ pháp luật.

## 2. Các tầng phân cấp

### Legal Entity — Pháp nhân

#### Commercial Legal Person — Pháp nhân thương mại

- Công ty TNHH một thành viên
- Công ty TNHH hai thành viên trở lên
- Công ty cổ phần
- Công ty hợp danh
- Các tổ chức kinh tế khác đủ điều kiện pháp nhân

#### Non-commercial Legal Person — Pháp nhân phi thương mại

- Cơ quan nhà nước
- Tổ chức chính trị, tổ chức chính trị - xã hội
- Quỹ xã hội, quỹ từ thiện
- Các tổ chức phi thương mại khác

### Related Organizations — Chủ thể tổ chức khác

- Doanh nghiệp tư nhân
- Hộ kinh doanh
- Chi nhánh
- Văn phòng đại diện
- Địa điểm kinh doanh
- Tổ chức nước ngoài

> Không phải mọi tổ chức kinh doanh đều là pháp nhân. Doanh nghiệp tư nhân không có tư cách pháp nhân. Chi nhánh và văn phòng đại diện cũng không phải pháp nhân độc lập. Cần đối chiếu điều kiện pháp nhân tại Bộ luật Dân sự 2015 và quy định chuyên ngành.

## 3. Mô hình phân tích trường hợp có 1 tỷ đồng

Cần phân biệt ít nhất năm lớp thông tin:

| Lớp | Ví dụ |
|---|---|
| Chủ thể | Công ty ABC |
| Tài sản | Khoản tiền gửi 1 tỷ đồng |
| Chủ tài khoản | Công ty ABC |
| Đại diện hợp pháp | Người đại diện theo pháp luật |
| Người thao tác | Người được ủy quyền giao dịch |

Không mặc định Tổng giám đốc là người đại diện theo pháp luật hoặc là người trực tiếp duyệt mọi giao dịch. Thông tin chủ tài khoản tổ chức, người đại diện hợp pháp, người được ủy quyền và người phụ trách kế toán cần được xác định theo hồ sơ ngân hàng và quy định áp dụng.

Tài khoản ngân hàng là một quan hệ tài sản giữa khách hàng và ngân hàng; số dư tài khoản không nên được hiểu đơn giản như tiền mặt đang nằm trong két của công ty.

## 4. Nguyên tắc phân biệt cốt lõi

- **Legal Person** không đồng nghĩa với chủ sở hữu hưởng lợi cuối cùng.
- **Legal Representative** không mặc nhiên là chủ sở hữu doanh nghiệp.
- Người có quyền truy cập Internet Banking không mặc nhiên có quyền sở hữu tiền.
- Quyền sở hữu cổ phần không đồng nghĩa với quyền sở hữu trực tiếp từng tài sản của công ty.
- Quyền sở hữu, quyền sử dụng, quyền quản lý và quyền kiểm soát là các quan hệ khác nhau.
- Có đăng ký doanh nghiệp không đồng nghĩa với có tư cách pháp nhân.
- Công ty mẹ và công ty con có thể là các pháp nhân riêng biệt dù có quan hệ sở hữu vốn.

## 5. Cấu trúc dữ liệu cho mỗi thuật ngữ

| Trường dữ liệu | Ví dụ |
|---|---|
| ID | LE-001 |
| Vietnamese | Pháp nhân |
| English | Legal Person |
| Definition | Chủ thể tổ chức được pháp luật công nhận tư cách pháp nhân |
| Category | Legal Entity |
| Parent | Legal Subject |
| Related Terms | Đại diện, tài sản, trách nhiệm |
| Legal Basis | Điều 74 Bộ luật Dân sự 2015 |
| Authority | Quốc hội hoặc cơ quan ban hành văn bản |
| Status | Còn hiệu lực / hết hiệu lực / cần xác minh |
| Verification | Đã đối chiếu văn bản / chưa đối chiếu |
| Evidence | Văn bản, hồ sơ, đăng ký hoặc chứng cứ liên quan |

### Các khái niệm cần phân biệt

- **Tên pháp lý (Legal Name):** Tên chính thức được đăng ký của tổ chức.
- **Danh tính pháp lý (Legal Identity):** Tập hợp thông tin xác định một chủ thể.
- **Pháp nhân (Legal Person):** Chủ thể có tư cách pháp nhân theo điều kiện luật định.
- **Pháp danh:** Thuật ngữ thường được dùng trong bối cảnh tôn giáo, không đồng nghĩa với tên pháp lý.
- **Người đại diện (Legal Representative):** Cá nhân nhân danh chủ thể trong phạm vi đại diện.
- **Người hưởng lợi cuối cùng (Ultimate Beneficial Owner):** Cá nhân cuối cùng có quyền sở hữu hoặc kiểm soát theo tiêu chí áp dụng.

## 6. Bộ thuật ngữ song ngữ nền tảng

| Tiếng Việt | English | Ý nghĩa |
|---|---|---|
| Chủ thể pháp luật | Legal Subject | Chủ thể có quyền và nghĩa vụ pháp lý |
| Pháp nhân | Legal Person | Tổ chức đáp ứng điều kiện có tư cách pháp nhân |
| Pháp nhân thương mại | Commercial Legal Person | Pháp nhân hoạt động vì mục tiêu lợi nhuận |
| Doanh nghiệp | Enterprise | Tổ chức kinh doanh theo pháp luật doanh nghiệp |
| Tên pháp lý | Legal Name | Tên chính thức được đăng ký |
| Mã số doanh nghiệp | Enterprise ID | Mã định danh doanh nghiệp |
| Chủ sở hữu | Owner | Chủ thể sở hữu |
| Cổ đông | Shareholder | Cá nhân hoặc tổ chức sở hữu cổ phần |
| Người hưởng lợi cuối cùng | Ultimate Beneficial Owner | Cá nhân cuối cùng có quyền sở hữu hoặc kiểm soát |
| Người đại diện theo pháp luật | Legal Representative | Cá nhân đại diện doanh nghiệp theo luật |
| Người đại diện theo ủy quyền | Authorized Representative | Người đại diện trong phạm vi ủy quyền |
| Người có thẩm quyền ký | Authorized Signatory | Người được trao quyền ký |
| Tài sản doanh nghiệp | Corporate Assets | Tài sản thuộc doanh nghiệp |
| Tài khoản thanh toán | Payment Account | Tài khoản được mở tại ngân hàng |
| Nghĩa vụ tài chính | Financial Obligation | Nghĩa vụ thanh toán, nộp thuế và nghĩa vụ khác |

Một số thuật ngữ tiếng Anh chỉ là bản dịch mô tả, không nhất thiết là chức danh hoặc khái niệm được định nghĩa độc lập trong pháp luật Việt Nam. Cần đối chiếu theo từng văn bản và tình huống.

## 7. Legal Knowledge Atlas — kiến trúc đề xuất

1. **Entity Recognition:** Nhận diện cá nhân, tổ chức, pháp nhân, doanh nghiệp.
2. **Identity Mapping:** Tên pháp lý, mã định danh, giấy phép, đăng ký.
3. **Ownership Mapping:** Chủ sở hữu, cổ đông, người hưởng lợi cuối cùng.
4. **Authority Mapping:** Đại diện, ủy quyền, thẩm quyền, chữ ký.
5. **Asset & Capital Mapping:** Tiền, tài khoản, vốn, tài sản, quyền tài sản.
6. **Obligation Mapping:** Hợp đồng, nghĩa vụ, khoản nợ, trách nhiệm.
7. **Regulatory Mapping:** Luật, nghị định, thông tư, cơ quan quản lý.
8. **Verification & Evidence:** Nguồn xác minh, điều luật, hiệu lực, chứng cứ.

## 8. Các bản đồ quan hệ chính

### Entity Atlas
Ai tồn tại về mặt pháp lý?

### Ownership Atlas
Ai sở hữu cái gì, theo loại quyền nào?

### Authority Atlas
Ai có quyền quyết định, ký, quản lý hoặc điều phối?

### Asset Atlas
Tài sản nằm ở đâu và thuộc quan hệ pháp lý nào?

### Obligation Atlas
Ai chịu trách nhiệm với ai, theo hợp đồng hoặc căn cứ nào?

## 9. Ví dụ minh họa doanh nghiệp

### Công ty cổ phần

- Có tư cách pháp nhân nếu đáp ứng điều kiện luật định.
- Có vốn điều lệ và cổ đông.
- Có tài sản độc lập với tài sản của cổ đông.
- Cổ đông sở hữu cổ phần, không trực tiếp sở hữu từng tài sản cụ thể của công ty.
- Công ty chịu trách nhiệm bằng tài sản của mình theo quy định pháp luật.

### Doanh nghiệp tư nhân

- Có tên doanh nghiệp và mã số doanh nghiệp.
- Có chủ doanh nghiệp tư nhân.
- Chủ doanh nghiệp chịu trách nhiệm bằng toàn bộ tài sản của mình.
- Không có tư cách pháp nhân.

### Chi nhánh

- Có tên chi nhánh, mã số đơn vị phụ thuộc và địa chỉ hoạt động.
- Có người đứng đầu và thực hiện nhiệm vụ theo phạm vi được giao.
- Không phải pháp nhân độc lập.
- Quyền và nghĩa vụ phát sinh được xác định trong quan hệ với pháp nhân chủ quản.

## 10. Phân tích một khoản tiền của doanh nghiệp theo tám lớp

Giả sử một doanh nghiệp nhận được 1 tỷ đồng từ hợp đồng bán hàng:

| Lớp | Đối tượng cần xác định |
|---:|---|
| 1 | Legal Subject — chủ thể pháp luật |
| 2 | Legal Identity — tên pháp lý, mã số doanh nghiệp |
| 3 | Ownership — cơ cấu sở hữu |
| 4 | Asset — khoản phải thu hoặc khoản tiền |
| 5 | Banking — tài khoản thanh toán của doanh nghiệp |
| 6 | Representation — người đại diện theo pháp luật |
| 7 | Authority — người được phân quyền ký, duyệt hoặc giao dịch |
| 8 | Accounting — doanh thu, công nợ và dòng tiền |

Mô hình khái quát:

```text
Legal Entity
    -> phát sinh quyền và nghĩa vụ tài sản
Corporate Asset / Khoản tiền 1.000.000.000 VNĐ
    -> được quản lý qua quan hệ tài khoản ngân hàng
Corporate Payment Account
    -> giao dịch theo thẩm quyền và cơ chế phê duyệt
Authorized Signatory / Authorized User
```

Đây là mô hình giả định để giải thích quan hệ pháp lý, không phải xác nhận số dư hoặc tài khoản cụ thể của bất kỳ doanh nghiệp nào. Doanh thu kế toán cũng không nhất thiết được ghi nhận đúng tại thời điểm tiền vào tài khoản.

## 11. Nguồn pháp luật và nguồn dữ liệu cần tra cứu

Không có một cơ sở dữ liệu duy nhất chứa toàn bộ khái niệm. Nên kết hợp:

- Cơ sở dữ liệu quốc gia về văn bản pháp luật.
- Cổng thông tin điện tử của Chính phủ.
- Cổng thông tin đăng ký doanh nghiệp.
- Công báo điện tử.
- Cơ sở dữ liệu văn bản pháp luật của Bộ Tư pháp.
- Hồ sơ đăng ký, điều lệ, nghị quyết, hợp đồng và tài liệu doanh nghiệp.
- Báo cáo tài chính, báo cáo thường niên và công bố thông tin chính thức.

### Văn bản nền tảng

- Bộ luật Dân sự 2015: chủ thể, pháp nhân, đại diện, tài sản và quyền đối với tài sản.
- Luật Doanh nghiệp 2020 và văn bản sửa đổi, bổ sung: cơ cấu doanh nghiệp, quản trị, sở hữu và đại diện.
- Quy định về tài khoản thanh toán và hoạt động ngân hàng.
- Quy định về kế toán, thuế, hóa đơn và đăng ký doanh nghiệp.

Tình trạng hiệu lực, điều khoản cụ thể và văn bản sửa đổi phải được kiểm tra tại nguồn chính thức trước khi sử dụng cho tư vấn hoặc giao dịch.

## 12. Quy tắc kiểm tra cho mỗi thông tin

Mỗi dữ liệu trong hệ thống cần trả lời được:

1. Có định nghĩa pháp luật không?
2. Có văn bản gốc không?
3. Có chủ thể cụ thể không?
4. Có chứng cứ sở hữu, đại diện hoặc kiểm soát không?
5. Quyền có giới hạn về thời gian, phạm vi hoặc điều kiện không?
6. Văn bản còn hiệu lực tại thời điểm tra cứu không?
7. Thông tin là quyền pháp lý, quyền theo hợp đồng hay chỉ là quyền truy cập kỹ thuật?

## 13. Hướng phát triển Legal Taxonomy 1.0 — Vietnam

Bộ dữ liệu mục tiêu gồm khoảng 20–30 nhóm lớn, phân tầng **L0–L5**, song ngữ Việt - Anh, với các trường:

- Định nghĩa chuẩn hóa.
- Thuật ngữ đồng nghĩa và liên quan.
- Quan hệ cha - con và quan hệ chéo.
- Căn cứ pháp luật.
- Cơ quan ban hành.
- Tình trạng hiệu lực.
- Thời điểm áp dụng.
- Ví dụ thực tế.
- Nguồn và chứng cứ xác minh.

Hệ thống có thể dùng cho:

- IT và quản trị dữ liệu.
- Kinh doanh và thành lập doanh nghiệp.
- Tài chính và kế toán.
- Ngân hàng và quản lý tài sản.
- Hợp đồng và giao dịch.
- Quản trị tổ chức và quyền kiểm soát.

## Kết luận

Khi phân tích một doanh nghiệp, một khoản tiền, một hợp đồng hoặc một tổ chức, cần xác định riêng biệt:

**Danh tính pháp lý → tư cách pháp nhân → cấu trúc sở hữu → quyền đại diện → thẩm quyền → tài sản → tài khoản → giao dịch → nghĩa vụ và trách nhiệm.**

Không đồng nhất quyền sở hữu với quyền kiểm soát, quyền đại diện với quyền hưởng lợi, hoặc quyền truy cập tài khoản với quyền sở hữu số dư. Mục tiêu của hệ thống là truy xuất xuyên suốt từ chủ thể đến tài sản, quyền hạn, giao dịch và trách nhiệm pháp lý, dựa trên văn bản và chứng cứ có thể kiểm tra.
