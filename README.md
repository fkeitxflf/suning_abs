# suning_abs
//  查询节点信息：  
curl http://localhost:46657/validators
// 查询区块信息  
curl http://localhost:46657/block?height=127
// 没有确认的交易数目  
curl http://localhost:46657/num_unconfirmed_txs
// 网络信息  
curl http://localhost:46657/net_info

curl -X POST  \
"http://localhost:8080/createAssetPoolOnChain" \
-H 'Content-type: application/json' \
-H 'abstractParam: 2222222222222' \
-H 'tocken: 11111111111111111111' \
-d '{"id":100}'