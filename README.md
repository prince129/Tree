# Tree
void preOrder(Node root) {
    Node temp = root;
    if(temp == null){
        return;
    }
        System.out.print(temp.data + " ");
        preOrder(temp.left);
        preOrder(temp.right);
}
