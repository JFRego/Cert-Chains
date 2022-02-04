#Making chained.crt files for vpn use

- after sign your cert (server.crt) with a subCA, create a chained.crt file;

        cat server.crt subca.crt > chained.crt
                - to use as a new server.crt
        
        
        
        
        
        
        
        
