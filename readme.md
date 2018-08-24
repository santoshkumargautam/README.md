#include<bits/stdc++.h>
#define ll long long
#define INF 1002000
#define mod 1000000007
using namespace std;

static int id = 1;

typedef struct timestamp{
	int day,month,year;
};

typedef struct node{
	int node_number;
	timestamp t;
	string node_id , referenceNodeId , childReferenceId , genesisReferenceid , HashValue;
};


int main(){
	
	//1.
	
	node * genesisNode = (node *)malloc(sizeof(node)); 
	genesisNode -> node_number =id;
	genesisNode -> node_id = to_string(id);
	genesisReferenceid = NULL;
	
	
}
