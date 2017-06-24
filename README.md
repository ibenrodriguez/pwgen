# pwgen
Password Generator written in PERL

Obtained from: http://www.securiteam.com/tools/5ZP0N20GAW.html

# gen.pl Password generator by nuTshell
# <carloslack at gmail dot com>
# http://nutshell.gotfault.net
#
# Part of eland(c) by posidron http://posidron.gotfault.net
#
# Gen was originally written to be part of Eland and then i`ve
# decided to publish this "user" version.
#
# Usage eg:
# $ ./gen.pl -all 8 3 join users.txt
# [!] Generating: Ge|{R[12
# [!] Generating: ;?#MMT%A
# [!] Generating: k8bW$RHx
#
# Passwords number: 3
# Passwords length: 8
# Output file pass_all.txt created
# Combo file combo.txt created
# $ cat users.txt
# root
# admin
# you
# $ cat combo.txt
# root:Ge|{R[12
# root:;?#MMT%A
# root:k8bW$RHx
# admin:Ge|{R[12
# admin:;?#MMT%A
# admin:k8bW$RHx
# you:Ge|{R[12
# you:;?#MMT%A
# you:k8bW$RHx
#

error in output - need to fix code: 

>perl pwgen.pl
Use of ?PATTERN? without explicit operator is deprecated at pwgen.pl line 91.
String found where operator expected at pwgen.pl line 94, near ")" . ""
        (Missing operator before " . "?)
String found where operator expected at pwgen.pl line 94, near "T" . ""
String found where operator expected at pwgen.pl line 107, near "all"){ while (1
)  {@array = @all ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 108, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 107)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 108, near "upchar"){ while
 (1)  {@array = @upchar ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 109, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 108)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 110, near """
  (Might be a runaway multi-line "" string starting on line 109)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 111, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 110)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 111, near "upint"){ while
(1)  {@array = @upint ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 112, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 111)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 113, near """
  (Might be a runaway multi-line "" string starting on line 112)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 114, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 113)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 115, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 114)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 115, near "upper"){ while
(1)  {@array = @upper ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 116, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 115)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 116, near "lower"){ while
(1)  {@array = @lower ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 117, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 116)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 117, near "uplower"){ whil
e (1)  {@array = @uplower ; $passoutputfile = ""
String found where operator expected at pwgen.pl line 118, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 117)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 119, near """
  (Might be a runaway multi-line "" string starting on line 118)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 120, near "if (Switch::cas
e ""
  (Might be a runaway multi-line "" string starting on line 119)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 121, near """
  (Might be a runaway multi-line "" string starting on line 120)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 128, near "open(PASSFILE,
""
  (Might be a runaway multi-line "" string starting on line 121)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 128, near "$passoutputfile
") or die ""
        (Missing operator before ") or die "?)
Scalar found where operator expected at pwgen.pl line 128, near "") or die "$!"
        (Missing operator before $!?)
Backslash found where operator expected at pwgen.pl line 128, near "$!\"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 133, near "$var .= ""
  (Might be a runaway multi-line "" string starting on line 128)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 135, near "print(""
  (Might be a runaway multi-line "" string starting on line 133)
        (Missing semicolon on previous line?)
Bareword found where operator expected at pwgen.pl line 135, near "] Generating"

        (Missing operator before Generating?)
Backslash found where operator expected at pwgen.pl line 135, near "$var\"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 136, near "print(PASSFILE
""
  (Might be a runaway multi-line "" string starting on line 135)
        (Missing semicolon on previous line?)
Scalar found where operator expected at pwgen.pl line 136, near "print(PASSFILE
"$var"
Backslash found where operator expected at pwgen.pl line 136, near "$var\"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 137, near "$var = ""
  (Might be a runaway multi-line "" string starting on line 136)
        (Missing semicolon on previous line?)
Backslash found where operator expected at pwgen.pl line 140, near "printf "\"
  (Might be a runaway multi-line "" string starting on line 137)
        (Do you need to predeclare printf?)
Backslash found where operator expected at pwgen.pl line 140, near "$PASSWORDNUM
BER\"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 141, near "printf ""
  (Might be a runaway multi-line "" string starting on line 140)
        (Missing semicolon on previous line?)
Bareword found where operator expected at pwgen.pl line 141, near "printf "Passw
ords"
        (Do you need to predeclare printf?)
Backslash found where operator expected at pwgen.pl line 141, near "$LOOPLENGTH\
"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 142, near "printf ""
  (Might be a runaway multi-line "" string starting on line 141)
        (Missing semicolon on previous line?)
Bareword found where operator expected at pwgen.pl line 142, near "printf "Outpu
t"
        (Do you need to predeclare printf?)
Bareword found where operator expected at pwgen.pl line 142, near "$passoutputfi
le created"
        (Missing operator before created?)
Backslash found where operator expected at pwgen.pl line 142, near "created\"
String found where operator expected at pwgen.pl line 148, near "my  @loop1 = `/
bin/cat $usersfile` or die ""
  (Might be a runaway multi-line "" string starting on line 142)
        (Missing semicolon on previous line?)
Bareword found where operator expected at pwgen.pl line 148, near "$\n"
        (Missing operator before n?)
String found where operator expected at pwgen.pl line 149, near "my  @loop2 = `/
bin/cat $passoutputfile` or die ""
  (Might be a runaway multi-line "" string starting on line 148)
        (Missing semicolon on previous line?)
Bareword found where operator expected at pwgen.pl line 149, near "$\n"
        (Missing operator before n?)
String found where operator expected at pwgen.pl line 150, near "open(COMBO, ""
  (Might be a runaway multi-line "" string starting on line 149)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 150, near "txt") or die ""

Scalar found where operator expected at pwgen.pl line 150, near "") or die "$!"
        (Missing operator before $!?)
Backslash found where operator expected at pwgen.pl line 150, near "$!\"
        (Missing operator before \?)
String found where operator expected at pwgen.pl line 154, near "print(COMBO ""
  (Might be a runaway multi-line "" string starting on line 150)
        (Missing semicolon on previous line?)
String found where operator expected at pwgen.pl line 158, near "printf(""
  (Might be a runaway multi-line "" string starting on line 154)
Global symbol "@upchar" requires explicit package name at pwgen.pl line 88.
syntax error at pwgen.pl line 91, near "=|="
  (Might be a runaway multi-line // string starting on line 88)
Global symbol "$passoutputfile" requires explicit package name at pwgen.pl line
128.
Global symbol "$array" requires explicit package name at pwgen.pl line 133.
Global symbol "$var" requires explicit package name at pwgen.pl line 135.
Global symbol "$var" requires explicit package name at pwgen.pl line 136.
Global symbol "$PASSWORDNUMBER" requires explicit package name at pwgen.pl line
140.
Global symbol "$LOOPLENGTH" requires explicit package name at pwgen.pl line 141.

Global symbol "$passoutputfile" requires explicit package name at pwgen.pl line
142.
Global symbol "$user" requires explicit package name at pwgen.pl line 154.
pwgen.pl has too many errors.
