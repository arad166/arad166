```ruby
eval$s=%w(s=%(eval$s=%w(#{$s}       )*"");func=->n{s.slice!(0,n)}
;fish="#29H7#29@#21A2                       3#21@#17R31#17@#14A37
#14@#11D13#7A23#1                               1@#9H12#11A24#9@#
8R12#11A26#8@#                                     6D12#9A32#6@#5
H12#6A37#5@             #4R12#5                       A40#4@#3D12
#8A39#3@#            2H13#9A39#2                        @#2R13#11
A37#2@#D            13#14A36#@#                          H14#15A3
4#@#R1            4#18A31#@                                #D14#2
1A28#            @#H15#                                     22A26
#@#R            16#25                                        A22#
@#D            18#25A20                                       #@#
2H             18#26A17#                                       2@
#2             R20#26A15#2                                     @#
             3D21#25A13#3@#                                    
              4H22#24A11#4@#5                                  
              R26#19A10#5@#6D29#                               
              15A9#6@#8H33#7A9#8@#9                            
               R47#9@#12A42#11@#14D37                          
                #14@#17A31#17@#21H23#21@#                      
                  30A5#30";output="";i=0;le                    
n=                  fish.size;i=0;len.times{c=                 fi
sh                    [i];if(c!='@'&&c!='#');j=i               +1
;l=                     "";(fish.size-j).times{|k             |if
(!(f                      ish[j]=~/[0-9]/));break;           end;
l<<fi                          sh[j];j+=1;};count=          l.to_
i;prin                             t(32.chr*count)         ;i=j;e
lsif(c==                                 "@");pr         int("\n"
);i+=1;el                                               se;j=i+1;
l="";(fish.s                                          ize-j).time
s{|k|if(!(fish                                     [j]=~/[0-9]/))
;break;end;l<<fis                               h[j];j+=1;};leng=
l.to_i;print(func[len                       g]);i=j;end;};puts();
#This_program_is_a_Ruby_quine.     ##arad166##Kento_Harada###)*""
```
