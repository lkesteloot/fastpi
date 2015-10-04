# Fast π

Fast π calculation, taken from
[this Futility Closet post](http://www.futilitycloset.com/2015/10/04/easy-pi/).
Calculates π to 100,000 digits and compares it to a reference value. Each iteration
takes about one second and there are 16 iterations. Run using the `GO` script:

    % ./GO

Change the value of `PRECISION` in the code to 50 to see the accuracy increase
with each iteration:

    % ./GO
    Accurate to 3 digits.
    3.1405792505221682483113312689758233117734402375129
    Accurate to 8 digits.
    3.1415926462135422821493444319826957743144372233456
    Accurate to 19 digits.
    3.1415926535897932382795127748018639743812255048354
    Accurate to 41 digits.
    3.1415926535897932384626433832795028841971146782836
    Accurate to 50 digits.
    3.1415926535897932384626433832795028841971693993751

