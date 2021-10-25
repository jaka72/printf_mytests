


make re

IN main() SELECT WHICH TEST :

	check_chars();
	// check_strings_all();
	// check_ints_all();
	// check_hex_all();
	// check_u_all();
	// check_p_all();
	// check_mixed();

run ./test_jaka_all

NEW SUBJECT:
    conversions: c s p d i u x X

    • %c print a single character.
    • %s print a string of characters.
    • %p The void * pointer argument is printed in hexadecimal.
    • %d print a decimal (base 10) number.
    • %i print an integer in base 10.
    • %u print an unsigned decimal (base 10) number.
    • %x print a number in hexadecimal (base 16), with lowercase.
    • %X print a number in hexadecimal (base 16), with uppercase.
    • %% print a percent sign

    BONUS:
        • Manage any combination of the following flags: ’-0.’ and minimum field width
            with all conversions
        • Manage all the following flags: ’# +’ (yes, one of them is a space)