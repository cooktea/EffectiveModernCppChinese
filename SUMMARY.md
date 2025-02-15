* [__类型推导__]()
	* [Item 1:理解模板类型推导](./1.DeducingTypes/item1.md)
	* [Item 2:理解auto类型推导](./1.DeducingTypes/item2.md)
	* [Item 3:理解decltype](./1.DeducingTypes/item3.md)
	* [Item 4:学会查看类型推导结果](./1.DeducingTypes/item4.md)
* [ __auto__]()
	* [Item 5:优先考虑auto而非显式类型声明](./2.Auto/item5.md)
	* [Item 6:auto推导若非己愿，使用显式类型初始化惯用法](./2.Auto/item6.md)
* [__移步现代C++__]()
	* [Item 7:区别使用()和{}创建对象](./3.MovingToModernCpp/item7.md)
	* [Item 8:优先考虑nullptr而非0和NULL](./3.MovingToModernCpp/item8.md)
	* [Item 9:优先考虑别名声明而非typedefs](./3.MovingToModernCpp/item9.md)
	* [Item 10:优先考虑限域枚举而非未限域枚举](./3.MovingToModernCpp/item10.md) 已修订
	* [Item 11:优先考虑使用deleted函数而非使用未定义的私有声明](./3.MovingToModernCpp/item11.md)
	* [Item 12:使用override声明重载函数](./3.MovingToModernCpp/item12.md)
	* [Item 13:优先考虑const_iterator而非iterator](./3.MovingToModernCpp/item13.md)
	* [Item 14:如果函数不抛出异常请使用noexcept](./3.MovingToModernCpp/item14.md)
	* [Item 15:尽可能的使用constexpr](./3.MovingToModernCpp/item15.md)
	* [Item 16:让const成员函数线程安全](./3.MovingToModernCpp/item16.md)
	* [Item 17:理解特殊成员函数函数的生成](./3.MovingToModernCpp/item17.md) 
* [__智能指针__]()
	* [Item 18:对于独占资源使用std::unique_ptr](./4.SmartPointers/item18.md)
	* [Item 19:对于共享资源使用std::shared_ptr](./4.SmartPointers/item19.md)
	* [Item 20:当std::shard_ptr可能悬空时使用std::weak_ptr](./4.SmartPointers/item20.md)
	* [Item 21:优先考虑使用std::make_unique和std::make_shared而非new](./4.SmartPointers/item21.md)
	* [Item 22:当使用Pimpl惯用法，请在实现文件中定义特殊成员函数](./4.SmartPointers/item22.md)
* [__右值引用，移动语义，完美转发__]()
	* [Item 23:理解std::move和std::forward](./5.RRefMovSemPerfForw/item23.md)
	* [Item 24:区别通用引用和右值引用](./5.RRefMovSemPerfForw/item24.md)
	* [Item 25:对于右值引用使用std::move，对于通用引用使用std::forward](./5.RRefMovSemPerfForw/item25.md)
	* [Item 26:避免重载通用引用](./5.RRefMovSemPerfForw/item26.md) 
	* [Item 27:熟悉重载通用引用的替代品](./5.RRefMovSemPerfForw/item27.md)
	* [Item 28:理解引用折叠](./5.RRefMovSemPerfForw/item28.md)
	* [Item 29:认识移动操作的缺点](./5.RRefMovSemPerfForw/item29.md)
	* [Item 30:熟悉完美转发失败的情况](./5.RRefMovSemPerfForw/item30.md)
* [__Lambda表达式__]()
	* [Item 31:避免使用默认捕获模式](./6.LambdaExpressions/item31.md)
	* [Item 32:使用初始化捕获来移动对象到闭包中](./6.LambdaExpressions/item32.md)
	* [Item 33:对于std::forward的auto&&形参使用decltype](./6.LambdaExpressions/item33.md)
	* [Item 34:优先考虑lambda表达式而非std::bind](./6.LambdaExpressions/item34.md)
* [__并发API__]()
	* [Item 35:优先考虑基于任务的编程而非基于线程的编程](./7.TheConcurrencyAPI/Item35.md)
	* [Item 36:如果有异步的必要请指定std::launch::threads](./7.TheConcurrencyAPI/item36.md)
	* [Item 37:从各个方面使得std::threads unjoinable](./7.TheConcurrencyAPI/item37.md)
	* [Item 38:关注不同线程句柄析构行为](./7.TheConcurrencyAPI/item38.md)
	* [Item 39:考虑对于单次事件通信使用void](./7.TheConcurrencyAPI/item39.md)
	* [Item 40:对于并发使用std::atomic，volatile用于特殊内存区](./7.TheConcurrencyAPI/item40.md)
* [__微调__]()
	* [Item 41:对于那些可移动总是被拷贝的形参使用传值方式](./8.Tweaks/item41.md)
	* [Item 42:考虑就地创建而非插入](./8.Tweaks/item42.md)
