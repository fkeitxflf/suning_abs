# suning_abs
//  ��ѯ�ڵ���Ϣ��  
curl http://localhost:46657/validators
// ��ѯ������Ϣ  
curl http://localhost:46657/block?height=127
// û��ȷ�ϵĽ�����Ŀ  
curl http://localhost:46657/num_unconfirmed_txs
// ������Ϣ  
curl http://localhost:46657/net_info

curl -X POST  \
"http://localhost:8080/createAssetPoolOnChain" \
-H 'Content-type: application/json' \
-H 'abstractParam: 2222222222222' \
-H 'tocken: 11111111111111111111' \
-d '{"id":100}'