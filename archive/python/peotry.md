poetry init
poetry add fastapi "uvicorn[standard]" sqlmodel typer pydantic
poetry add --group dev pytest httpx

poetry add alembic


poetry run adventure play --lang es
poetry run uvicorn app.main:app --reload

