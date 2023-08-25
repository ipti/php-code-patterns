# php-code-patterns

# PHPMD
## CLEAN CODE RULES
- **BooleanArgumentFlag:** Não devem ser passados como parâmetros de uma função, argumentos do tipo boolean com valor default.
- **StaticAccess:** Não declarar métodos com acesso estático `Method::method()`
- **IfStatementAssignment:** Não fazer atribuições de valor a variáveis em estruturas condicionais `if`
- **DuplicatedArrayKey:** Não definir um novo valor para uma chave de um array que já possui um valor atribuído.
- **ErrorControlOperator:** 

## CODE SIZE RULES
- **MissingImport:** 
- **UndefinedVariable:** 
- **CyclomaticComplexity:** 
- **NPathComplexity:** 
- **ExcessiveMethodLength (70):** 
- **ExcessiveClassLength (800):** 
- **ExcessiveParameterList (4):** 
- **ExcessivePublicCount (30):** 
- **TooManyFields:** 
- **TooManyMethods (25):** 
- **TooManyPublicMethods (10):** 
- **ExcessiveClassComplexity (50):** 

## CONTROVERSIAL RULES
- **CamelCaseClassName:** 
- **CamelCasePropertyName:** 
- **CamelCaseMethodName:** 
- **CamelCaseParameterName:** 
- **CamelCaseParameterName:** 

## DESIGN RULES
- **ExitExpression:** 
- **EvalExpression:** 
- **GotoStatement:** 
- **NumberOfChildren:** 
- **DepthOfInheritance:** 
- **zCouplingBetweenObjects:** 
- **zDevelopmentCodeFragment:** 
- **EmptyCatchBlock:** 
- **CountInLoopExpression:** 

# NAMING RULES
- **LongClassName(max: 40):** Declarar classes com nomes de no máximo 40 caracteres e no mínimo 3 caracteres.
- **ShortClassName(min: 3):** Declarar classes 
- **LongVariable(max: 20):**
- **ShortVariable(min: 3):**
- **ShortMethodName(min: 3):**
- **ConstrutorWithNameAsEnclosingClass:**
- **ConstantNaming:**

## UNUSED CODE RULES
- **UnusedPrivateField:**
- **UnusedLocalVariable:**
- **UnusedPrivateMethod:**
- **UnusedFormalParameter:**


