install:
	docker-compose -f docker-compose.builder.yml run --rm install
setup:
	docker volume create nodemodules
dev:
	docker-compose up
yadd:
	DEPENDENCY=${D} docker-compose -f docker-compose.builder.yml run --rm yadd
nadd:
	DEPENDENCY=${D} docker-compose -f docker-compose.builder.yml run --rm nadd
