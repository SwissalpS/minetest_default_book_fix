# [default_book_fix]
A mod for Minetest overriding default:book handling to avoid item loss on save.

Players can accidentally switch wielded item while opening a formspec. Then when
they save, the book will overwrite whatever item they had in that slot.
This mod also covers the case where user drops the book(-stack) while formspec is
opening.

