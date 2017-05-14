# ProductFinderService
Product finder service is a REST based spring boot microservice. It takes a product name query parameter and return the lowest current available price. The price for comparison will be found by querying and comparing results from Best Buy and Walmart using the supplied API keys. If there are multiple products, the lowest priced product will be returned.
