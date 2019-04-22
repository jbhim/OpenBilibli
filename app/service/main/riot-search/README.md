# riot-search-service

# 项目简介
1.riot（搜索引擎）是一个全内存的搜索引擎，riot （搜索引擎）只存储业务唯一标识(如稿件的aid)，以及需要进行搜索的字段(如稿件的标题)
2.给定搜索范围(业务唯一标识的集合，如aid的集合，此字段为可选项，不给定搜索范围则全量搜索)，以及搜索的关键字，返回搜索的结果(搜索命中的关键字，以及搜索的结果)
3.提供分页，按搜索相关性排序等


# 编译环境
go 1.10

# 依赖包
github.com/go-ego/riot

# 编译执行
go build main.go