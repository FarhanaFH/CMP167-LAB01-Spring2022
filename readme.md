# Classes/Type/ADT: A written description of the attributes and behaviors of an object 
## Blueprint 
# Object: An instance of a class.
## A physical representation of the blueprint
# Attributes: Instance Variables
# Behaviors: Instance Methods
# behaviors: Instance Methods
## Syntax:

	accessModifier class NameofClass{
	
	
	
#Behaviors: Constructors, setters & getters, equals, toString, compareTo
# Constructors: It is a special method, that shares the same name as the class, it does not have a return type, it initializes the instance variable and instantiate the object
# Setters: Mutators, it modifies the value of the instance variables 
# Getters: Accessors, they retrieve the values of the instance variables


# Four pillars of OOPL: Polymorphism, Encapsulation, Abstraction,  inheritance 

 - Polymorphism: Poly = Multiple, morphism =forms, 
 - Encapsu;ation: Limiting the access to data by encapsulating it in private attributes and controlling accessThrough setters and getters
 
 	public class mammal{
 		private int numOflegs;
 		private boolean hasFur;
 		private String species;
 		
 		public Mammal () { 
 			 this.numofLegs = 2; 
 			  this.hasFur = true; 
 			  this species = "bear";
 			  }
 			  
 			 public Mammal (int numofLegs, boolean hasFur, String species)
 			 this.numOfLegs = numofLegs; 
 			 this.hasFur = has Fur;
 			 this.specoes = species;
 			 
 			 
 		public void set NumOfLegs (int numOfLegs) { this.numOfLegs = numOfLegs;
 			  
 			} 
 			   
 			public int getNumOfLegs () { 
 				return this.numOfLegs; 
 		}
 
 	}
 	
 	