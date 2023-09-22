#include <iostream>
#include <sstream> 
#include <bits/stdc++.h>
#include <unordered_map>
#include <map>

using namespace std;



int main(){
    
    string pilihan;
    int menu,menu2;
    cout<<"1.Desimal ke Biner\n2.Desimal ke Heksadesimal\n3.Desimal ke Oktal\n";
    
    while(menu==1){
    
    
    getline(cin,pilihan);
    
    if(pilihan=="1"||pilihan=="desimal ke biner"||pilihan=="biner"||pilihan=="bi"||pilihan=="BINER"||pilihan=="Biner"){
        int nilai_biner,i,j;        //cara menkonversi bilangan desimal ke bilangan biner//
        string hasil;
        cout<<"masukkan bilangan desimal\n";
        cin>>nilai_biner;
        i=nilai_biner;
        cout<<"nilai biner\n";
        while(i!=0){
            j=i%2;
            string huruf=to_string(j);
            hasil += huruf;
            i=i/2;
            }
        reverse(hasil.begin(),hasil.end());
        cout<<hasil<<"\nTekan 1 untuk kembali\nTekan tombol apa saja untuk berhenti\n ";
        
        cin>>menu2;
            if(menu2==1){
                menu=1;
            }
            else
                return 0;
    }
        
    

    else if(pilihan=="2"||pilihan=="desimal ke Hexadesimal"||pilihan=="hexa"||pilihan=="he"||pilihan=="HEXADESIMAL"||pilihan=="Hexadesimal"){
        int nilai_biner,i,j;        //cara menkonversi bilangan desimal ke bilangan hexadesimal//
        string hasil,A,aca;
        cout<<"masukkan nilai bilangan desimal\n";
        cin>>nilai_biner;
        i=nilai_biner;
        map<string,string>dictionary;
        
        cout<<"nilai hexadesimal\n";
        while(i!=0){
            j=i%16;
            string huruf=to_string(j);
            dictionary["10"] = "A";
            dictionary["11"] = "B";
            dictionary["12"] = "C";
            dictionary["13"] = "D";
            dictionary["14"] = "E";
            dictionary["0"] = "0";
            dictionary["1"] = "1";
            dictionary["2"] = "2";
            dictionary["3"] = "3";
            dictionary["4"] = "4";
            dictionary["5"] = "5";
            dictionary["6"] = "6";
            dictionary["7"] = "7";
            dictionary["8"] = "8";
            dictionary["9"] = "9";
            dictionary.find(huruf);
            string aca=dictionary[huruf];
            hasil += aca;
            i=i/16;
            }
        reverse(hasil.begin(),hasil.end());
        cout<<hasil<<"\nTekan 1 untuk kembali\nTekan tombol apa saja untuk berhenti\n ";
        
        cin>>menu2;
            if(menu2==1){
                menu=1;
            }
            else
                return 0;}

    else if(pilihan=="3"||pilihan=="desimal ke "||pilihan=="oktal"||pilihan=="ok"||pilihan=="OKTAL"||pilihan=="Oktal"){
        int nilai_biner,i,j;        //cara menkonversi bilangan desimal ke bilangan hexadesimal//
        string hasil,A,aca;
        cout<<"masukkan nilai bilangan desimal\n";
        cin>>nilai_biner;
        i=nilai_biner;
        map<string,string>dictionary;
        cout<<"oktal\n";
        while(i!=0){
            j=i%8;
            string huruf=to_string(j);
            hasil += huruf;
            i=i/8;
            }
        reverse(hasil.begin(),hasil.end());
        
        cout<<hasil<<"\nTekan 1 untuk kembali\nTekan tombol apa saja untuk berhenti\n ";
        
        cin>>menu2;
            if(menu2==1){
                menu=1;
            }
            else
                return 0;}
    
    }  
return 0;
}
