# blockchain
Desenvolvimento da blockchain

rodar com python3 node.py  


Obter o blockchain  
GET:  http://localhost:5001/get_chain  
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
{  
	"user": "user_id",  
	"data": {}  
}  


