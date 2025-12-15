class Node:
    def __init__(self,value):   #self will be new_node, value will be 7
        self.value = value
        self.next = None    #new node class just to create empty node

class LinkedList:
    def __init__(self, value):     #self will be my_linked_list, value will be 7
        new_node = Node(value)
        self.head= new_node
        self.tail =new_node
        self.length =1
        
