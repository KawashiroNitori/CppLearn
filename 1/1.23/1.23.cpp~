#include <iostream>
#include "Sales_item.h"
using namespace std;

int main()
{
	Sales_item curBook,preBook;
	int count=0;
	cin>>preBook;
	while (cin>>curBook)
		if (preBook.isbn()==curBook.isbn())
			count++;
		else
		{
			cout<<"Book "<<preBook.isbn()<<" occurs "<<count<<" times.\n";
			count=1;
			preBook=curBook;
		}

	return 0;
}
