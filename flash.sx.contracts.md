<h1 class="contract">borrow</h1>

---
spec_version: "0.2.0"
title: borrow
summary: 'Borrow from flashloan provider'
icon: https://raw.githubusercontent.com/stableex/sx.flash/master/icons/sx.png#716d4470028412d9cf498649dfcc8180d546be43c2811014e202eae5584fe6f8
---

Flashloan borrower {{to}} agrees to repay {{contract}}@{{quantity}} within the same transaction timeframe.

The borrow transfer action will be using {{memo}} memo and notify {{notifier}} account.

<h1 class="contract">checkbalance</h1>

---
spec_version: "0.2.0"
title: checkbalance
summary: 'Check account balance if lower than quantity'
icon: https://raw.githubusercontent.com/stableex/sx.flash/master/icons/sx.png#716d4470028412d9cf498649dfcc8180d546be43c2811014e202eae5584fe6f8
---

Throws error if {{account}} as a balance of lower than {{contract}}@{{quantity}}.