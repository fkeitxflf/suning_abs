# suning_abs
//  ��ѯ�ڵ���Ϣ��  
curl http://localhost:46657/validators
// ��ѯ������Ϣ  
curl http://localhost:46657/block?height=127
// û��ȷ�ϵĽ�����Ŀ  
curl http://localhost:46657/num_unconfirmed_txs
// ������Ϣ  
curl http://localhost:46657/net_info

curl -X POST \
http://localhost:8081/createAssetPoolOnChain \
-H 'Cache-Control: no-cache' \
-H 'Content-Type: application/json' \
-H 'Postman-Token: 3438665b-d0d7-fb4b-ad3f-552ec8b2bb95' \
-H 'abstractParam: 22222222222' \
-H 'token: 11111111111' \
-d '{"id":1,
    "assets":[
    	{
			"projectId":1,
			"projectName":"cmx",
			"contractCode":"gg",
			"valueDay":"ss",
			"startDay":"ww",
			"dueDay":"ww",
			"corpus":2.0,
			"oddCorpus":3.7,
			"interestRateTypeCode":1,
			"interestRate":2.8,
			"repaymentTypeCode":1,
			"paymentFrequencyCode":12,
			"name":"sd",
			"age":12,
			"credentialsTypeCode":3,
			"credentialsCode":"ss",
			"levelCode":1,
			"currentOverdueDays":1,
			"currentOverdueTimes":1,
			"overdueDaysTotal":1
    	}
    ]
} '


2.�ʽ�ز�ѯ

curl -X POST \
http://localhost:8081/queryAssetPoolOnChain \
-H 'Cache-Control: no-cache' \
-H 'Content-Type: application/json' \
-H 'Postman-Token: 940a4701-9a75-d173-efe0-2a317eb0efe8' \
-H 'abstractParam: 22222222222' \
-H 'token: 11111111111' \
-d '{
	"id":1
} '