bool comp(char cad[])
{
	int numcad = strlen(cad);

	bool sign = true, npunt = true, exc = ((numcad == 0) || (numcad == 1 && (cad[0] == '+' || cad[0] == '-' || cad[0] == '.')) || (numcad == 2 && (cad[0] == '+' || cad[0] == '-') && cad[1] == '.'));

	if (exc)
	{
		return false;
	}

	for (int i = 0; i < numcad; i++)
	{
		switch (cad[i])
		{
		case '-':
			if (!sign)
			{
				return false;
			}
			break;
		case '+':
			if (!sign)
			{
				return false;
			}
			break;
		case '.':
			if (npunt)
			{
				npunt = false;
			}
			else
			{
				return false;
			}
			break;
		case '0':
			break;
		case '1':
			break;
		case '2':
			break;
		case '3':
			break;
		case '4':
			break;
		case '5':
			break;
		case '6':
			break;
		case '7':
			break;
		case '8':
			break;
		case '9':
			break;
		default:
			return false;
		}
		sign = false;
	}
	return true;
}
