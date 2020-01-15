---
title: Transferring Money to Another Account
keywords: unofficial YNAB guide, recording income and expenses
last_updated: July 3, 2019
toc: false
sidebar: mydoc_sidebar
permalink: mydoc_transferring_money.html
folder: mydoc
---

When you have multiple accounts, sometimes you need to transfer funds from one account to another. For example, you have set up an emergency savings plan. Then you might transfer a certain monthly amount from a [Checking account](mydoc_account_types), which is the primary account you spent from, to a [Savings account](mydoc_account_types) that you set up specifically for this purpose. If you are paying out a loan, you might transfer loan payments from a [Checking account](mydoc_account_types) to an off-budget [Other Loan or Liability account](mydoc_account_types).

Transferring money between two [budget accounts](mydoc_account_types.html#account-categories) means moving it within the budget. This action does not change the [budget balance](mydoc_budget_balance). Transferring money from a budget account to an [off-budget](mydoc_account_types.html#account-categories) one, however, creates an expense because it takes the funds out of the budget. Similarly, moving money from an off-budget account to a budget one creates income because it brings the funds into the budget.


## To transfer money to another account:

1.  In the blue navigation pane on the left, select an account from which you want to make a transfer. <br/>This opens a list of account transactions.

2.  In the transactions list, click **Make a transfer**. <br/>This creates an empty transfer transaction.
    {% include image.html file="MakeTransfer.png" alt="Transfer transaction" %}

3.  Fill in the details:
    *  **Date**. Set the date of the transfer.
    *  **Payee**. From the drop-down list, select an account to which you want to make a transfer.
    *  **Category**. Depending on whether you transfer the money between budget or off-budget accounts, follow one of the options:
        *  <span style="color: #155f88"><b>Budget to budget</b></span>. Because you are not spending the money but merely moving it between accounts, leave the **Category** field empty.
        *  <span style="color: #155f88"><b>Budget to off-budget</b></span>. Select a [budget category](mydoc_about_categories) from the drop-down list.
        *  <span style="color: #155f88"><b>Off-budget to off-budget</b></span>. You will not see the **Category** field. Transactions in off-budget accounts do not have budget categories.
        *  <span style="color: #155f88"><b>Off-budget to budget</b></span>. You will not see the **Category** field. Transactions in off-budget accounts do not have budget categories.
    *  **Memo**. Add a personal note (optional).
    *  **Outflow**. Specify the transfer amount in the **Outflow** field.
    *  **Inflow**. Leave the **Inflow** field empty.
        {% include image.html file="TransferTransaction.png" alt="Transferring money" %}

        {% include tip.html content="Optionally, you can [color tag a transaction](mydoc_tagging_transactions) by clicking the dimmed flag on the left side and selecting one of the offered colored flags." %}

4. Click **Save**. <br/>For all types of transfers, except **off-budget to budget** transfers, this completes the process of transferring money to another account. For **off-budget to budget** transfers, proceed with [completing the transfer](#to-complete-a-transfer-from-an-off-budget-account-to-a-budget-one).

## To complete a transfer from an off-budget account to a budget one:

1.  In the blue navigation pane on the left, select a budget account to which you just made a transfer. <br/>This opens a list of account transactions.

2.  In the transactions list, follow the notifications and assign a [budget category](mydoc_about_categories) to the transfer transaction in one of the following ways:
    *  Click the **Category** field and select a category from the drop-down list.
    *  Click the orange **info (i)** button and select a category in the pop-up box.
        {% include image.html file="TransferNotification.png" alt="Finishing the transfer transaction" %}

3.  Click **Done**.

{% include links.html %}
