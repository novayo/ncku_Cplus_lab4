Question A:
	average(double * n1, double & n2)	---->	_Z7averagePdRd
	average(int n1, float n2)			---->	_Z7averageif

Question B:
	char	沒有特別去定義的話都是1bytes
	int		是以32bits去儲存資料，故是4bytes
	float	是以32bits去儲存資料，故是4bytes
	double	是以64bits去儲存資料，故是8bytes
	pointer	用於儲存位置，而在64bits電腦中，位置是以64bits去表示（也就是8bytes），所以任何型態的pointer都會是8bytes，也就是為什麼sizeof(pointer) = 8（相反的32bits電腦中，都是4）
