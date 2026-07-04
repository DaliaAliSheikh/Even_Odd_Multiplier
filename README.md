# 🔢 فحص ناتج الضرب (زوجي أم فردي) - Even or Odd Multiplier

برنامج يعتمد على الدوال والشروط؛ يطلب من المستخدم إدخال رقمين، ويقوم بضربهما، ثم يفحص ناتج الضرب لمعرفة هل هو رقم زوجي أم فردي باستخدام عامل الباقي `%2`.

### 💻 كود البرنامج:
```python
def multiply_numbers():
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    return num1 * num2

# الحصول على ناتج الضرب وفحصه
multiplication_result = multiply_numbers()
print(f"Result: {multiplication_result}")

if multiplication_result % 2 == 0:
    print("رقم زوجي")
else:
    print("رقم فردي")
