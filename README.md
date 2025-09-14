```ruby
eval$s=%w(s=%(eval$s=%w(#{$s})*""     );func=->n{s.slice!(0,n)};fish="
#33H5#32@#22A26#22@#17                          R36#17@#13A44#13@#10D5
0#10@#8A14#12H28#                                    8@#6A12#16R30#6@#
5A10#15D35#5@                                            #3A10#9H45#3@
#2A10#11R4                                                  5#2@#2A9#1
5D42#2@#              A10#20H38#@#                            A11#24R3
3#@#A1            1#29D28#@#A13#33                              H22#@#
A15#3          5R18#@#2A17#36D                                   13#2@
#3A          20#35H10#                                             2@#
4A          24#31R8#3@#                                             5A
32         #22D6#5@#6A41#9                                          H8
          #6@#8A54#8@#11R49#10                                      
           @#13A44#13@#17D36#17@#22                                 
           A26#22@#34H2#34";output="";i=                            
             0;len=fish.size;i=0;len.times{c=f                      
               ish[i];if(c!='@'&&c!='#');j=i+1;spa                  
ce                 _len="";(fish.size-j).times{|k|if(!(             fi
sh[                    j]=~/[0-9]/));break;end;space_len<<          fi
sh[j                        ];j+=1;};count=space_len.to_i;p        rin
t(32.                                chr*count);i=j;elsif(c      =="@"
);prin                                         t("\n");i        +=1;el
se;j=i+1                                                      ;l="";(f
ish.size-j)                                                 .times{|k|
if(!(fish[j]=                                            ~/[0-9]/));br
eak;end;l<<fish[j                                    ];j+=1;};let_len=
l.to_i;print(func[let_                          len]);i=j;end;};puts()
;#This_program_is_a_Ruby_quine.___  ___##arad166##Kento_Harada####)*""
```
