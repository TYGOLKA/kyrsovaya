Запускал свои коды на Jupiter Notebooks, ниже ссылка на онлайн Jupiter

Ссылка на Online Jupiter Notebooks:
https://cocalc.com/features/jupyter-notebook



Код с рисунка 1: (ответ: [5 - y])

from sympy import symbols, Eq, solve
x, y = symbols('x y')
equation = Eq(x + y, 5)
solution = solve(equation, x)
solution



Код с рисунка 2: (ответ: {x: 4, y: 1})

from sympy import symbols, Eq, solve
x, y = symbols('x y')
equation = Eq(x + y, 5)
solution = solve([Eq(x + y, 5), Eq(x - y, 3)], (x, y))
solution



Код с рисунка 3: (ответ: -cos(x)

from sympy import symbols, Eq, solve, sin, diff, integrate
x = symbols('x')
expression = sin(x)
derivative = diff(expression, x)
integral = integrate(expression, x)
integral



Код с рисунка 4: (ответ: 10)

from sympy import symbols, Eq, solve, binomial

binomial_coefficient = binomial(5, 2)
binomial_coefficient



Код с рисунка 5: (ответ: ∣ϕ⟩A∣ψ⟩)

from sympy.physics.quantum import Dagger, Operator, Bra, Ket

A = Operator('A')
ket_psi = Ket('psi')
bra_phi = Bra('phi')
expectation_value = Dagger(bra_phi) * A * ket_psi
expectation_value
