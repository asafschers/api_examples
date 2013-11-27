```ruby
Stripe::Charge.create(amount: 100, 
		      currency: 'usd',
		      customer: 'cus_2xRw4xWkm7ybdg',
		      metadata: {shipping_address: '{"name": "Dennis Duffy", 
		                                     "city": "San Francisco",
		                                     "line1": "1 main st",
		                                     "line2": "",
		                                     "phone":"917-917-9177",
		                                     "zip":"12345",
		                                     "state":"CA",
		                                     "country":"US",
		                                     "company":""}', 
		                 billing_company: '',
		                 billing_phone: '917-917-9177',
		                 email: 'dev@riskified.com',
		                 browser_ip: '200.123.123.113'})
```

