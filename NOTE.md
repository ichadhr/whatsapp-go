// make base 64
628187887353554:83e4060e-78e1-4fe5-9977-aasdccd46a2b8

curl --request GET \
  --url http://127.0.0.1:3000/api/v1/whatsapp/auth \
  --header 'Authorization: Basic NjI4MTg3ODg3MzUzNTU0OjgzZTQwNjBlLTc4ZTEtNGZlNS05OTc3LWFhc2RjY2Q0NmEyYjg='



curl --request POST \
  --url http://127.0.0.1:3000/api/v1/whatsapp/login \
  --header "Authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJkYXRhIjoiNjI4MTg3ODg3MzUzNTU0IiwiZXhwIjoxNjI0NTM4OTUwfQ.hvcD0x_7LmuyOLvet_RfS-2ri-YHpCevP6Cci37JIgSO7Nwji1-272I4ZhxBjy3gBNZdyxq3LuBLKqcxoctTx54EB3tGxE_D8bzefGHyenmz1CJwavHi_RTzKxtwCZl0JQeCqHWAicG-QnO2-lR3JAPPwmJBceARwNfbLhSm_utGIIdOhWJFe-Ft8d_Kf2VCHEwClWh9LA4Y2pVIhQvsEWtHUGjJdgVFRuZxu6lBA5z1gJZJ6ZvdkJXi_jklvfJgYHO0JAPpODNau1B_m8N5G4BYaFcYA-ciACPWqhN8SE1j0yON0PtU_Yk0ARKwnmINpwrMc2ateXycV0y-eEi1CA" \
  --header 'Content-Type: application/x-www-form-urlencoded' \
  --data output=html



  curl --request POST \
  --url http://127.0.0.1:3000/api/v1/whatsapp/send/text \
  --header 'Authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJkYXRhIjoiNjI4MTg3ODg3MzUzNTU0IiwiZXhwIjoxNjI0NTM4OTUwfQ.hvcD0x_7LmuyOLvet_RfS-2ri-YHpCevP6Cci37JIgSO7Nwji1-272I4ZhxBjy3gBNZdyxq3LuBLKqcxoctTx54EB3tGxE_D8bzefGHyenmz1CJwavHi_RTzKxtwCZl0JQeCqHWAicG-QnO2-lR3JAPPwmJBceARwNfbLhSm_utGIIdOhWJFe-Ft8d_Kf2VCHEwClWh9LA4Y2pVIhQvsEWtHUGjJdgVFRuZxu6lBA5z1gJZJ6ZvdkJXi_jklvfJgYHO0JAPpODNau1B_m8N5G4BYaFcYA-ciACPWqhN8SE1j0yON0PtU_Yk0ARKwnmINpwrMc2ateXycV0y-eEi1CA' \
  --header 'Content-Type: application/x-www-form-urlencoded' \
  --data msisdn=6281388114554@s.whatsapp.net \
  --data 'message=hai'