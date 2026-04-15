# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** AI20K-2A202600486
**Name:** Nguyễn Tiến Huy Hoàng
**Date:** 16/04/2026

---

## 1. Ket qua thi nghiem

Chay `agent_simulation.py` voi 2 bo du lieu va ghi lai ket qua:

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) | Based on my data, the best choice is Laptop at $1200. | 9 | Data đã được validate nên kết quả hợp lý |
| Garbage Data (`garbage_data.csv`) | Based on my data, the best choice is Nuclear Reactor at $999999. | 2 | Bị ảnh hưởng bởi outlier và data lỗi |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

(Viet nhan xet cua ban o day — it nhat 50 tu)

(Hay phan tich cac van de nhu Duplicate IDs, wrong data types, outliers, null values
va giai thich tai sao chung anh huong den ket qua cua Agent.)

---

## 3. Ket luan

**Quality Data > Quality Prompt?** (Dong y hay khong? Giai thich ngan gon.)

(Viet ket luan cua ban o day)
