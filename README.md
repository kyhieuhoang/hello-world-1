Node someFunction(Node root, int key) {
  if (root == null || root.key == key) {
    return root;
  }

  if (root.key > key) {
    return someFunction(root.left, key);
  }

  return someFunction(root.right, key);
}
