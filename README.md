#Proje Unix-tabanlı derleme ortamı için geliştirilmiştir (gcc, flex, bison, make).


#macOS üzerinde derlenip test edilmiştir.

#Windows üzerinde WSL’de aynı şekilde çalıştırılabilir.

#fact.vsl fib.vsl test.vsl tes2.vsl derlenmiştir ve çıktılar vam sanal makinesinde başarıyla çalıştırılıp sonuç alınmıştır.


#1) Derleyiciyi oluşturmak için:                            make vc
  
#2) Örnek VSL programını derlemek için:                     ./vc program.vsl

    

# 3) VAS assembler ile makine kodu üretmek için:             ./vas program.vas

   

#4) Programı VAM sanal makinesinde çalıştırmak için:         ./vam program.vam

    
    #Önemli Not: Program dosyalarının farklı dizinlere taşınması durumund dosya yolları manuel olarak güncellenmelidir.Derleyici varsayılan olarak bulunduğu dizinde dosya üretir.



