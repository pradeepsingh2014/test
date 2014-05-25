test
====

def add_phn(self):      #TO ADD PHN NO &amp; TO CHECK THE VALIDITY OF PHN NO ie 10 digit         lop=[]              #stores list of phn_no         choice=True         while choice:             self.phn_no=input('Enter the phn no.')             if len (str(self.phn_no))==10:                 lop.append(self.phn_no)                 choice=raw_input("Contact saved.,want to add more--> press y or enter to exit:")             else:                 return "Pls enter valid phn no."         return lop
