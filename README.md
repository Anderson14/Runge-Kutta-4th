# Runge-Kutta-4th
Método Numérico de Runge-Kutta 4th para Sistemas de Equações Diferenciais Ordinárias

function [t, x, y, z] = RungeKutta4th(EDO1, EDO2, EDO3, t0, tf, h, x0, y0, z0)
         t(1) = t0;             % Tempo Inicial
         x(1) = x0;             % Valor inicial de x
         y(1) = y0;             % Valor inicial de y
         z(1) = z0;             % Valor inicial de z
         n = (tf - t0)/h;       % Número de pontos da discretização
         
end
