#Good for minimizing boilerplate code, improving readability
from dataclasses import dataclass


@dataclass (order=True)
class Month:
    year: int
    month: int

    def __str__(self):
        return f'{self.month:02}/{self.year}' # :02 for formatting specification


a = Month(year=2030, month=2)

feb2030 = Month(2030,2)
feb2030
print('A:'+ str(a) + ' feb:'+ str(feb2030))
