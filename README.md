# gestinnaire.py
gestionnaire
class Client
 
  def_init_(self ,n = 0,solde = 0.0):
   self._numero = n;
   self._solde = n;
   
 def_get_numero(self) 
    print ("Numero du client est : {0}")
    return self._numero
    
 def_get_solde(self)
    print ('Solde est de : {0} FCFA")
    return self._solde
    
 def_set_solde(self ;new_solde)
    printf ("Votre solde est de {0} FCFA")
    self._solde = new_solde
    
 def infoSolde(self)
    print ("Votre solde est de {0} FCFA!")
    
 def versement(self , add)
    self._solde += add
    print ("Versement de {} FCFA éffectué.")
    self.infoSolde()
    
 def retrait (self , moins)
    self._solde -= moins
    print ("Le montant débité est de {} FCFA.")
    self.infosolde()
    
 solde = property(_get_solde, _set_solde)
 numero = property(_get_numero)
    
