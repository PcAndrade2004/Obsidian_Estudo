#### Struct DateTime 
* Representa um momento no tempo expresso como uma **data** e **hora**
* Uma variável do tipo DateTime é um tipo de valor e possui um valor padrão
* O valor padrão de um DateTime é: **01/01/0001 00:00:00**
* Ao usar DateTime a representação para o português do brasil usa o formato : 
<font color="#ff0000">dd/mm/aaaa hh:mm:ss</font>  

#### Obtendo a Data Atual 
* Podemos obter a data e hora atual da seguinte forma
* Aqui usamos a propriedade ***Now*** que vai exibir a representação da data e hora atual.
```Csharp
DateTime dataAtual = DateTime.Now;

Console.WriteLine(dataAtual);
```

#### Criando Data especifica
Usando o operador ***new*** pra criar uma data especifica que deve ser especificada no formato <font color="#ff0000">(<font color="#ff0000">aaaa,mm,dd</font>)</font>

#### Definindo a Data e Hora 
Podemos definir a data e a hora usando o formato: <font color="#ff0000">(aaaa,mm,dd, hh:mm:ss)</font>
```Csharp
DateTime dataHoraAtual = new DateTime(2025,06,25,18,51,22);

Console.WriteLine(dataHoraAtual);
```

## Operações com Data e Hora 

1 - Extrair informações como *dia*, *mês*, *hora*, *ano*
* <font color="#ff0000">	Year, Month ,Day, Hour, Minute, Second, Millisecond</font>
```Csharp
//Extraindo informações Console.WriteLine("\n===Extraindo informações===");  
Console.WriteLine(dataAtual.Year);  
Console.WriteLine(dataAtual.Month);  
Console.WriteLine(dataAtual.Day);  
Console.WriteLine(dataAtual.Hour);  
Console.WriteLine(dataAtual.Minute);  
Console.WriteLine(dataAtual.Second);  
Console.WriteLine(dataAtual.Microsecond);
```
2 - Adicionar dias, horas, mês, anos
* <font color="#ff0000">AddDays, AddHours, AddMonths, AddYears</font>
```Csharp
//adicionando valores Console.WriteLine("\n===Adicionando valores===");  
Console.WriteLine(dataAtual.AddDays(2));  
Console.WriteLine(dataAtual.AddHours(1));  
Console.WriteLine(dataAtual.AddMonths(2));  
Console.WriteLine(dataAtual.AddYears(2));
```

3 - Obter dia da semana e do ano
* <font color="#ff0000">DayOfWeek, DayOfYear</font>
```Csharp
//Obtendo o dia da Semana e o Ano Console.WriteLine("\n===Obtendo o dia da Semana e o Ano===");  
Console.WriteLine(dataAtual.DayOfWeek);  
Console.WriteLine(dataAtual.DayOfYear);
```

4 - Expressar **data** no formato longo e abreviado
* <font color="#ff0000">ToLongDateString, ToShortDateString</font>
     Longo                         Abreviado
 ```Csharp
//Obtendo Data no formato longo e abreviado  
Console.WriteLine("\n===Obtendo Data no formato longo e abreviado===");  
Console.WriteLine(dataAtual.ToLongDateString());  
Console.WriteLine(dataAtual.ToShortDateString());
```

5- Expressar Hora no formato longo e abreviado
* <font color="#ff0000">ToLongHoursString</font>, <font color="#ff0000">ToShortDateString</font>
```Csharp
//Obtendo Hora no formato longo e abreviado  
Console.WriteLine("\n===Obtendo Hora no formato longo e abreviado===");  
Console.WriteLine(dataAtual.ToLongTimeString());  
Console.WriteLine(dataAtual.ToShortTimeString());
```

## Criando Date no formato **dia/mês/ano**
* Se você quiser exibir a data no formato **dia/mês/ano** (como usamos no Brasil), deve usar:
```Csharp
data.ToString("dd/MM/yyyy")
```

