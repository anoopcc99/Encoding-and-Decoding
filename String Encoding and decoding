import base64
jh=1
a=int(input("Enter the key :"))
if a==1234:
    print("Key accepted, program is Running....")
    def main():
        print('1.Encode \n2.Decode \n ')
        d=int(input('Enter the choice :'))
        if d==1:
            ck=input("Enter the desired text file in .txt format to use :")
            cn=input("Enter the text to Encode :")
            cn=base64.b64encode(cn.encode(encoding='UTF-8',errors='strict'))
            with open(ck,'wb') as f1:
                f1.write(cn)
                f1.write(b'\n')
            print('Encoded text :')
            print(cn)
        else:
            e=input('Enter the file name to decode :')
            with open(e,'rb') as f2:
                u=f2.readlines()
                for i in range(2):
                    h=base64.b64decode(u[i])
                    h=h.decode('UTF-8')
                    return(h)
while(jh!=0):
    kk=main()
    print(kk)
