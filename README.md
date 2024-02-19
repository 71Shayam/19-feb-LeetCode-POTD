 bool isPowerOfTwo(int n) {
        for( int i = 0 ; i<=30 ; i++){
            int ans = pow(2,i) ;
            if ( ans == n){ // agara 2 ki power mai vo no aa gya aur n ko equal aa gya to true mark krdena
                return true ;
            }
        }
       return 0 ;
    }
