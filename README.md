<!-- Alignment -->
<div align="center">
  <!-- Banner -->
  <img width="1197" height="119" alt="DBTCTOR" src="https://github.com/user-attachments/assets/851084e9-fae3-4aaa-909e-a10d7b004bc3" />
  <!-- Caption -->
  <h3>Heart Plugin</h3>

  <!-- Divider -->
  ---

  <h3>Has someone stolen your heart?</h3>

  <a href="./script.js" target="_blank">`script.js`</a> now includes the ability to add hearts to debt.
  
</div>

<!-- Code -->
 ```js
  if (res.totalMoney > 0 && res.totalHearts > 0) {
    tot.textContent = `Total Debt: ${formatCurrency(res.totalMoney)} + ❤️${res.totalHearts.toFixed(2)}`;
  } else if (res.totalMoney > 0) {
    tot.textContent = `Total Debt: ${formatCurrency(res.totalMoney)}`;
  } else if (res.totalHearts > 0) {
    tot.textContent = `Total Debt: ❤️${res.totalHearts.toFixed(2)}`;
  } else {
    tot.textContent = `Total Debt: $0.00`;
  }
```
<!-- Divider -->
---

<!-- Alignment -->
<div align="center">
  <!-- Fork Button -->
  <a href="https://github.com/Debtector/Debtector" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/Fork-Debtector?style=for-the-badge&logo=GitHub&color=%23348543"></a>
</div>

