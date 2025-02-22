#include<iostream>
using namespace std;
class Node{
    public:
    int val;
    Node* left;
    Node* right;
    Node(int data){
        val=data;
        left=NULL;
        right=NULL;
    }

};    
Node* Createtree(){
    cout<<"Enter the root data ";
    int data;
    cin>>data;
    if(data==-1) return NULL;
    Node* root=new Node(data);
    cout<<"Enter left side of data ";
    root->left=Createtree();
    cout<<"Enter right side of data ";
    root->right=Createtree();
}
int main(){
  Node* a=Createtree();
}
