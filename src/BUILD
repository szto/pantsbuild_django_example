pex_binary(
    name="django-admin",
    dependencies=[
        "3rdparty#Django",
    ],
    script="django-admin",
)

python_sources()

pex_binary(
    name="manage",
    entry_point="manage.py",
    dependencies=[
        "src/superman:superman",
        "src/polls:polls"
    ],
    inherit_path='prefer'
)


