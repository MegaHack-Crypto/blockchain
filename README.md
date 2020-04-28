# blockchain
Desenvolvimento da blockchain

rodar com python3 node.py  


Obter o blockchain  
GET:  http://localhost:5001/get_chain  
Return
{  
	"chain":[	{	"index":1,  
				"previous_hash":"0",  
				"proof":1,  
				"timestamp":"2020-04-27 20:26:44.008018",  
				"transactions":[]  
			}  
		]  
	,"length":1  
}  


Inserir dados  
POST:  
http://localhost:5001/add_transaction  
Payload
{  
	"user": user_id,  
	"public_key", public_key,  
	"data": {...}  
}  


