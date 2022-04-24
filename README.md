# 445_Akash_CodeUpload
A repository containing code upload necessary for PPS Sem 2 J2 Section
# Code Upload From Hackerrank
### Problem 1
`
int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    float km,m,ft,in,cm;
    scanf("%f",&km);
    m=km*1000.0;
    ft=km*1000.0*3.28084;
    in=km*1000.0*3.28084*12.00000575;
    cm=km*1000.0*100.0;
    printf("%.2f m\n%.2f ft\n%.2f in\n%.2f cm",m,ft,in,cm);
    return 0;
}
`

### Problem 2
`
int main() {
        
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */  
    int m,n,o;
    scanf("%d %d",&m,&n);
    o=(m*n)%2;
    printf("%d",(m*n)/2+o);
    return 0;
}
`
### Problem 3
`
int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */ 
    float sqft,acre;
    scanf("%f",&sqft);
    acre=sqft/43500.0;
    printf("%.2f sq.ft is equal to %.2f acres",sqft,acre);
    return 0;
}
`
### Problem 4
`
int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    int amt,amtgiv,div,rem;
    scanf("%d\n%d",&amt,&amtgiv);
    div=amt/amtgiv;
    rem=amt%amtgiv;
    printf("Quotient:%d\nRemainder:%d",div,rem);
    return 0;
}
`
### Problem 5
`
int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    int tot,d,h,m,s;
    scanf("%d",&tot);
    d=tot/60/60/24;
    h=(tot-d*24*60*60)/60/60;
    m=(tot-d*24*60*60-h*60*60)/60;
    s=tot-d*24*60*60-h*60*60-m*60;
    printf("The Duration is %d days %d hours %d minutes %d seconds",d,h,m,s);
    return 0;
}
`
All code was done using C language

}
