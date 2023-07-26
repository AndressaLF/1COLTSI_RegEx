# Atividade 5 - Validação de Email

Objetivo: O objetivo desta atividade é praticar a criação de expressões regulares para validar endereços de e-mail.

Para um e-mail ser valido é necessário seguir as premissas abaixo:
1. Conter um único símbolo "@" separando o nome de usuário do domínio
2. O nome de usuário (antes do "@") pode conter letras (maiúsculas e minúsculas), dígitos numéricos, pontos (.), hífens (-) e underscores (_).
3. O nome de usuário não pode começar ou terminar com um ponto (.), hífen (-) ou underscore (_).
4. O domínio (parte após o "@") deve conter apenas letras (maiúsculas e minúsculas), dígitos numéricos e pontos (.).
5. O domínio não pode começar ou terminar com um ponto (.).
6. O domínio deve ter pelo menos um ponto (.), e o último segmento após o último ponto deve ter no mínimo dois caracteres (por exemplo, ".com", ".net" ou "uk").

## Lista de Emails para validação

john.doe@example.com       
jane@company          
user123@example.com           
@example.com          
johndoe@1234           
mary.smith@example.com            
user@company.com.            
contact@company.com                   
john.doe@.com            
info@website.org            
user@company..com             
sales@business.com           
jane.doe@company.           
support@domain.com             
user@.com           
jennifer12@example.co.uk            
@example           
contact.us@example.com            
jane@.com           
admin@company.net           
user@example.            
testuser@example.com             
jane.doe@company           
sales@company.net                 
contact@website           
user@company.net        
john.doe@company.       



# Lista de Emails Válidos