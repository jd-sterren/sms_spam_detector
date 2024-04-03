# sms_spam_detector

## Results of the following text messages. 

---

1. You are a lucky winner of $5000!
--- Not Spam
2. You won 2 free tickets to the Super Bowl.
--- Not Spam
3. You won 2 free tickets to the Super Bowl text us to claim your prize.
--- Spam
4. Thanks for registering. Text 4343 to receive free updates on medicare.
--- Spam

## Program Changes
To avoid "FutureWarning: The default value of `dual` will change from `True` to 
`'auto'` in 1.5. Set the value of `dual` explicitly to suppress the warning."
</br>
Use LinearSVC(dual=True) instead of just LinearSVC()