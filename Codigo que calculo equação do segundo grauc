#include <stdio.h>
#include <math.h>
#define pi 3.14
int
main ()
{
  float a, b, c;
  printf ("digite o valor de a\n");
  scanf ("%f", &a);
  printf ("digite o valor de b\n");
  scanf ("%f", &b);
  printf ("digite o valor de c\n");
  scanf ("%f", &c);
  float delta;
  delta = (b * b) - (4 * a * c);
  if (a == 0)
    {
      printf ("isso nao eh uma equaC'C#o do segundo grau");
    }
  else if (delta >= 0)
    {
      float x1 = (-b + sqrt (delta)) / (2 * a);
      float x2 = (-b - sqrt (delta)) / (2 * a);
      printf ("o valor de x1 eh %.2f\n o valor de x2 eh  %.2f\n e o valor de delta eh %.2f", x1, x2,delta);
    }
  else
    {
      printf ("nao eh possivel determinar as raizes pois delta eh negativo");
    }
  return 0;
}

