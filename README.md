# ds-problems
all problems related to ds and algo

preorder traversal code:(gfg)
 public static void preOrder(Node root) {
        if(root==null)return;
        System.out.print(root.data+" ");
        preOrder(root.left);
        preOrder(root.right);
    }

